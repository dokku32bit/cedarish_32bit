# Cedarish
Heroku "Cedar-ish" 32bit Base Image for Docker


This build is forked from the [original by progrium](https://github.com/progrium/cedarish) to build against a 32bit base image
Latest information can be obtained from the original repository


### Further information
This is the source for a Docker image used for environments emulating the Heroku Cedar stacks. It's based on the official [Heroku stack images scripts](https://github.com/heroku/stack-images).

It doesn't include any buildpacks, just the base environment. This allows us to build a separate builder container and runner container. See [Herokuish](https://github.com/gliderlabs/herokuish) for emulating the rest of the Heroku build process.


