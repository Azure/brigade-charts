
# Brigade Charts

Helm charts for the [Brigade](https://github.com/brigadecore/brigade) project have been moved to
[brigadecore/charts](https://github.com/brigadecore/charts).

During the transitional phase, we will continue to serve an index file in this repo pointing
to the new chart URL.  However, future chart releases will not be added to this repo.

All subsequent chart releases will be served at the new URL: `https://brigadecore.github.io/charts`

Please update your local Helm repo:

  ```
  helm repo remove brigade
  helm repo add brigade https://brigadecore.github.io/charts
  ```

This `Azure/brigade-charts` repo will be deleted after the transition is complete.

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
