## VS Code Extensions from the TypeScript Team

## Deployment

The extensions are deployed to the vscode extension after a merge as _preview_ builds.

#### The Token Stopped Working

Each access token lasts _180 days_. Which means, every half-year this token needs to be refreshed. To do this, have a TypeScript team member to https://dev.azure.com/TypeScript/_usersSettings/tokens to create a new token ([vscode's info on the process is here](https://code.visualstudio.com/api/working-with-extensions/publishing-extension#get-a-personal-access-token)). (The key detail is to set Marketplace to manage") This token is then placed into the [GitHub Secrets](https://github.com/microsoft/TypeScript-VSCode-Extensions/settings/secrets/actions) section.

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

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
