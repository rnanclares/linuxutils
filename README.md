# linuxutils
Useful commands for linux bash terminal

## Rename Pictures using find and exiv2

```find . -iname '*.JPG' -exec exiv2 mv {} \;```

## Rename subfolders that match a particular name (raster)
The -n parameter performs a dry run
```find . -type d -name raster -exec rename -n -v raster ortho {} ";"```

