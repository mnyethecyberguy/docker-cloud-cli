# Cloud CLI Tools

My Docker container for Cloud CLI Tools.

This Dockerfile builds on a Ubuntu image and installs CLI tools for interacting with AWS, Azure, and GCP:

- `awscliv2` - AWS CLIv2
- `azure-cli` - Microsoft Azure CLI
- `gcloud` - Google Cloud SDK

The image also creates and runs under a non-root user.

## Using the Image

You can build the image yourself using this Dockerfile or pull from [Docker Hub](https://hub.docker.com/r/mnyethecyberguy/cloud-cli)

```
docker pull mnyethecyberguy/cloud-cli
```