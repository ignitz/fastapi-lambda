# Fast-API with Lambda

Tutorial from https://www.youtube.com/watch?v=6fE31084Uks&t=300s


Where packages are install on docker.

```
/usr/local/py-utils/shared/lib/python3.8/site-packages/
```

Run outside of container to create lambda-layers

```
bash ./create-lambda-layer.sh -v "python3.8" -n "fastapi-layer" -d "FastAPI Layer"
```
