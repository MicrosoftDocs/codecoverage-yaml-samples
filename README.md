# Settings for Code Coverage reporting in Azure Pipelines

<!-- 
Guidelines on README format: https://review.docs.microsoft.com/help/onboard/admin/samples/concepts/readme-template?branch=master

Guidance on onboarding samples to docs.microsoft.com/samples: https://review.docs.microsoft.com/help/onboard/admin/samples/process/onboarding?branch=master

Taxonomies for products and languages: https://review.docs.microsoft.com/new-hope/information-architecture/metadata/taxonomies?branch=master
-->

[Azure Pipelines](https://docs.microsoft.com/en-us/azure/devops/pipelines/?view=azure-devops) provides code coverage reporting. This experience can be tweaked using a settings YAML file (named  azurepipelines-coverage.yml) included at the root of your repo. 

Each of the folders in this repo contains a sample file for changing a setting.

| File/folder                               | Description                                                                         |
|-------------------------------------------|-------------------------------------------------------------------------------------|
| `SetDiffCoverageTarget`                   | Change the diff coverage threshold for pull requests.                               |
| `EnableCoverageDetailComments`            | Post details about lines covered/not covered for each code file in a pull request.  |
| `DisableCodeCoveragePullRequestStatus`    | Opt out of code coverage pull request capability.                                   |

## Related docs

* [Code coverage for pull requests](https://docs.microsoft.com/en-us/azure/devops/pipelines/test/codecoverage-for-pullrequests?view=azure-devops)
 
## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
