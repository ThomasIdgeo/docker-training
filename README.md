# Docker training

This is some training support for an introduction to Docker.
Slides are in French.

## Clone the repository
There are some submodules. So if you want to clone it properly, run
```
git clone --recurse-submodules https://github.com/jeanpommier/docker-training.git
```

## latex folder
The source slides are written in latex, using the beamer package.
Use a latex compiler to generate the PDF output (if update needed). You probably
can use Overleaf (online latex editor) if you ndon't have latex available on
your computer

## compos folder
This is where I've stored some compositions, to use with docker-compose. There are some submodules :
* qgisserver are my experimentations about qgisserver & matching web client. This is a work in progresse, but the lizmap flavor works (see docker-compose.yml file in it)
* dockerfiles/geoserver is, like the name says, a Dockerfile to build a geoserver image. This is not intended to be used in production as-is. It is training material only (would need at least some cleanup before we can use it in production)
