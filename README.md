# Taskserver container

[![Build Status](https://travis-ci.org/coaxial/docker-taskserver.svg?branch=master)](https://travis-ci.org/coaxial/docker-taskserver) [![](https://images.microbadger.com/badges/image/coaxial/taskserver.svg)](https://microbadger.com/images/coaxial/taskserver "Get your own image badge on microbadger.com")

This is an Alpine container with taskd (taskwarrior server).

It is intended as a base image.

Rebuilt whenever `alpine:latest` is.

# Volumes

- `/var/taskd` (which is also the value set for `$TASKDDATA`)
