# Bower with cache

Docker image with npm, bower and npm-cache.

- Working directory: `/app`
- Cache directory: `/cache`

#### Sample execution:

```
docker run --rm -v $(pwd):/app -v /tmp/npm-cache:/cache ludekvesely/bower-cache
```

