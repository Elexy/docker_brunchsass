docker brunch sass
==================

docker container build for brunch.io with sass

install with:
`docker pull  elexy/docker-brunchsass`

to run brunch from your current directory:
```docker run -i -t -v `pwd`:/var/www/ -w /var/www seretalabs/brunchsass bash```
to also expose port 3333:
```docker run -i -t -p 3333:3333 -v `pwd`:/var/www/ -w /var/www seretalabs/brunchsass bash```

While inside the container you can do:
`brunch w -s`

