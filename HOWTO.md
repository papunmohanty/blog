## Modify the website and verify with following command
```sh
cd blog/myblog/

# modify contents, and check the working website with the command
hugo server
```

## Generate the Build Contents
```sh
# gruvhugo is the theme being used in the blog
hugo -t gruvhugo
```

## Go to public, make commit and push to sub repository
```sh
cd public
g add .
g commit -am"Add: new gif image"
g push
```

## Also comit new changes in blog
```sh
cd ../..
g add .
g commit -am"Add: new gif image"
g push
```