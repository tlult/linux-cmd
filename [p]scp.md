##### Transfer directory
>* no / after directory name,  or only the files get transferred.
>* no / nor same folder name needed at the target
>* -v for verbose

    [p]scp -r [-v] name@ip:/path/to/directory /local/where/to/put


##### Transfer single file

    [p]scp /local/file.xxx name@ip:/where/to/put
