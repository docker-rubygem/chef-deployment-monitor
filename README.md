[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/chef-deployment-monitor.svg)](https://hub.docker.com/r/rubygem/chef-deployment-monitor/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/chef-deployment-monitor.svg)](https://hub.docker.com/r/rubygem/chef-deployment-monitor/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/chef-deployment-monitor.svg)](https://hub.docker.com/r/rubygem/chef-deployment-monitor/)
[![Gem Downloads](https://img.shields.io/gem/dt/chef-deployment-monitor.svg)](https://rubygems.org/gems/chef-deployment-monitor/)
# chef-deployment-monitor

Auto-Generated Docker image for chef-deployment-monitor to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/chef-deployment-monitor`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/chef-deployment-monitor`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/chef-deployment-monitor`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/chef-deployment-monitor/)
