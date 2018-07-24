# Ranger for Gargoyle

*Based off the following GitHub repo: https://github.com/coheigea/testcases/tree/master/apache/docker/ranger*

This is a project for **TESTING** purposes. Currently the changes made to the default images listed above are:
- Add Ranger s3 plugin (see dependencies below)
- Add service definition at runtime for s3
- Set logging of ranger service to debug (you can find the logs in the container here: `/opt/ranger-1.0.0-admin/ews/logs/ranger-admin-*-.log`)

## How to run

`docker-compose up`

## Dependencies

- s3 plugin for Ranger: https://github.com/bolkedebruin/rangers3plugin.git