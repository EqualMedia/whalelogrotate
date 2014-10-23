# whalelogrotate

Docker container logs can grow infinitely. This container runs logrotate in a
while loop every 30 minutes and rotates log files. See logrotate config file.

## Configuration

None at this point.

## Running

```bash
$ docker run --name whalelogrotate -v /var/lib/docker/containers:/srv/docker-logs state/whalelogrotate
```
