# PoC GraalVM native with Distroless base image

A simple PoC for using one of the [Google's Distroless images](https://github.com/GoogleContainerTools/distroless) as a base for a Java app build as native image.

Commands:

- Clean: `make clean`
- Build: `make build`
- Docker SBOM: `docker sbom ninckblokje/poc-graalvm-distroless:latest`

