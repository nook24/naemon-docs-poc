# Naemon Website

# Build the Docker image
```
docker build . -t naemon/mkdocs
```

Run the docs
```
docker run --rm -it -v "$PWD":/docs -w /docs -p 8000:8000 naemon/mkdocs
```

Open in Browser
```
http://127.0.0.1:8000/
```