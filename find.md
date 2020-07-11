File count in the directory and sub-directory

    [sudo] find . -type f -print | wc -l

Exclude a direcoty form the count

    find . -type f -not -path "./WPimages/*" -print | wc -l
