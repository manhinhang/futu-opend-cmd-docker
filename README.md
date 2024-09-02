# FutuOpenD Cmd

Run FutuOpenD command in a Docker container.

## Build

```bash
docker build -t futu-opend-cmd .
```

## Run

```bash
docker run -v /var/run/docker.sock:/var/run/docker.sock -ti futu-opend-cmd ${FUTU_OPEND_CMD}
```
