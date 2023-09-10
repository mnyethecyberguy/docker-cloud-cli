# Cloud CLI Tools

My Docker container for Cloud CLI Tools.

This Dockerfile builds on a Ubuntu image and installs CLI tools for interacting with AWS, Azure, and GCP:

- `awscliv2` - AWS CLIv2
- `azure-cli` - Microsoft Azure CLI
- `gcloud` - Google Cloud SDK

The image also creates and runs under a non-root user.

Latest build on my Docker Hub: [mnyethecyberguy/cloud-cli](https://hub.docker.com/r/mnyethecyberguy/cloud-cli)