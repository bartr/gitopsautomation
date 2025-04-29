# GitOps Automation

## Overview

- GitOps Automation development branch

## Prerequisites

- Git CLI
- DotNet 8.0 SDK

## Quick Start

- Fork this repo and clone the fork
- Change to the repo directory (default: ./gitopsautomation)
- Install the sample GitOps Automation tool

```bash

dotnet tool install --global GitOpsAutomation --version 0.3.2

# if you get a nuget source missing error
# dotnet nuget add source https://api.nuget.org/v3/index.json -n nuget.org

# run the GitOpsAutomation tool
goa

# list the clusters
goa list clusters

# list the applications
goa list applications

# list the clusters in ring 0
goa eval -e "/m/ring/0"

# re-generate the GitOps manifests
goa gen
git status

```

## Support

This project uses GitHub Issues to track bugs and feature requests. Please search the existing issues before filing new issues to avoid duplicates. For new issues, file your bug or feature request as a new issue.

## Contributing

This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit <https://cla.opensource.microsoft.com>.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party's policies.
