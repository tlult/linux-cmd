##### Change computer date time

    sudo date -s "$(wget -qSO- --max-redirect=0 google.com 2>&1 | grep Date: | cut -d' ' -f5-8)Z"

##### Tar
###### tar and compress a directory

    tar czvf [filename].tar.gz path/to/directory
    
###### untar and decompress a directory
 
    tar zxvf [filename].tar.gz
    
