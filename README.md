# linuxutils
Useful commands for linux bash terminal

## Rename Pictures using find and exiv2

```find . -iname '*.JPG' -exec exiv2 mv {} \;```

## Rename subfolders that match a particular name (raster)

```find . -type d -name raster -exec rename -v raster ortho {} ";"```

