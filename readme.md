## Docker Janitor

Script to cleanup unused docker images. Primarily used for build systems. Requires `ts` for logging timestamp.

----

#### Schedule Example

    */20 * * * * /opt/janitor/janitor >> /var/log/janitor.log
