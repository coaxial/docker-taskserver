# Taskserver container

This is an Alpine container with taskd (taskwarrior server).

It is intended as a base image.

Rebuilt whenever `alpine:latest` is.

# Volumes

- `/var/taskd` (which is also the value set for `$TASKDDATA`)
