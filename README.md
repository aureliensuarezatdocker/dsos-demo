# dsos-demo

A one-page site that shows the Docker whale. It exists to demonstrate the
Docker-Sponsored Open Source review agent end to end: the agent reads this
repository for the source code and the licence, and reads
[aureliensuarez/dsos-demo](https://hub.docker.com/r/aureliensuarez/dsos-demo)
on Docker Hub for the public image and the activity date.

It is not a real project and nobody depends on it.

## Run it

```bash
docker run --rm -p 8080:80 aureliensuarez/dsos-demo
```

Then open http://localhost:8080.

## Build it

```bash
docker build -t aureliensuarez/dsos-demo .
```

## Licence

MIT. See [LICENSE](LICENSE).
