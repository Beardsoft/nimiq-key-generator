# nimiq-key-generator

This is a simple tool to generate Nimiq key pairs. it uses the default Nimiq tools to generate key pairs.
Make sure you mount /keys from the container to your host to keep the keys.

## Usage

```bash
docker run -it --rm -v $(pwd)/keys:/keys ghcr.io/maestroi/nimiq-key-generator:main
```

## License
