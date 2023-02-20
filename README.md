# upload-docker-action

### how to use

```
# .github/workflows/xxx.yaml

name: ***

...

jobs:
  job-name:
    runs-on: ***
    steps:

      ...


      - name: 'Docker upload'
        uses: how2flow/upload-docker-action@{ref}
        with:
          distro: ***
          path: *** # Dockerfile's path.
          username: ${{ secrets.DOCKERHUB_USERNAME }}
          password: ${{ secrets.DOCKERHUB_TOKEN }}
          repo: ***
          release: ***

...

```

#### contact:
- e-mail: <how2soft@gmail.com>
