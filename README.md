docker brunch sass
==================

docker build for brunch.io with sass

install with:
`docker pull seretalabs/brunchsass`

to run brunch from your current directory:
```docker run -i -t -v `pwd`:/var/www/ -w /var/www seretalabs/brunchsass bash```

While inside the container you can do:
`brunch w -s`

