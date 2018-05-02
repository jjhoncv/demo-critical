# demo-critical

```
docker run -it --rm -v $(pwd)/test:/usr/local/app -e ENV=[environment] -e CONFIG=/config micro-critical-css:1.0 node index
```
environment could be dev, pre, prod
