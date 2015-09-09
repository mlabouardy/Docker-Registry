# Docker-Registry
Store and distribute docker images

<img src="https://themacwrangler.files.wordpress.com/2014/11/screen-shot-2014-12-05-at-3-37-43-pm.png?w=516"/>


# Usage

```
docker run -p 5000:5000 mlabouardy/registry:latest
```

This will store the workspace in /tmp/registry. All Registry data lives in there.
You will probably want to make that a persistent volume (recommended):

# Questions?

Jump on devup.labouardy.com and Ask!
