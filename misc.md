##### Change computer date time

    sudo date -s "$(wget -qSO- --max-redirect=0 google.com 2>&1 | grep Date: | cut -d' ' -f5-8)Z"

##### Tar
###### tar and compress a directory

    tar czvf [filename].tar.gz path/to/directory
    
###### untar and decompress a directory
 
    tar zxvf [filename].tar.gz

##### gzip
gzip compress a single file, resulting a .gz file

##### rsync
>* -n for dry run
>* -a for preserve all original settings
>* -v for verbose

    rsync -avn --progress sourcefolder destinationfolder --exclude thefoldertoexclude --exclude anotherfolder

##### ln
creates multiple sym links in the current directory(.) pointing to all(\*) first-level items (either directories or files)
    ln -s /full/path/to/TARGET/Directory/* .
