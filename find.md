File count in a directory and sub-directories

    [sudo] find . -type f -print | wc -l

Exclude a directory form the count

    find . -type f -not -path "./WPimages/*" -print | wc -l
