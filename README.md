# Create Go Docker Image

``` bash
cd hello
# Builds the image with the pack command, takes in the current working directory
pack build go-test --builder  paketobuildpacks/builder:tiny
```

View the completed image and run it.

``` bash
docker images
docker run go-test

```

Expected Output: 

`Don't communicate by sharing memory, share memory by communicating.`

