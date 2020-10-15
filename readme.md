[Exporting the extension list in VS Code](https://stackoverflow.com/questions/35773299/how-can-you-export-vs-code-extension-list)

```bash
# Run the command on the machine you want to backup
code --list-extensions | xargs -L 1 echo code --install-extension

## Sample output code --install-extension aws-scripting-guy.cform
code --install-extension bungcip.better-toml
code --install-extension burkeholland.simple-react-snippets
code --install-extension christian-kohler.npm-intellisense
code --install-extension christian-kohler.path-intellisense
code --install-extension CoenraadS.bracket-pair-colorizer-2
code --install-extension cpylua.language-postcss
code --install-extension DavidAnson.vscode-markdownlint
code --install-extension dbaeumer.vscode-eslint
code --install-extension dkundel.vscode-npm-source
code --install-extension dsteenman.cloudformation-yaml-snippets
code --install-extension dsznajder.es7-react-js-snippets
code --install-extension eamodio.gitlens
code --install-extension erd0s.terraform-autocomplete
code --install-extension esbenp.prettier-vscode
code --install-extension formulahendry.auto-close-tag
code --install-extension formulahendry.auto-rename-tag
code --install-extension gencer.html-slim-scss-css-class-completion
code --install-extension golang.go
code --install-extension googlecloudtools.cloudcode
code --install-extension hjb2012.vscode-es6-string-html
code --install-extension JamesBirtles.svelte-vscode
code --install-extension jpoissonnier.vscode-styled-components
code --install-extension kisstkondoros.csstriggers
code --install-extension mgmcdermott.vscode-language-babel
code --install-extension mikestead.dotenv
code --install-extension mquandalle.graphql
code --install-extension ms-azure-devops.azure-pipelines
code --install-extension ms-azuretools.vscode-azureappservice
code --install-extension ms-azuretools.vscode-azurefunctions
code --install-extension ms-azuretools.vscode-azureresourcegroups
code --install-extension ms-azuretools.vscode-azurestorage
code --install-extension ms-azuretools.vscode-azureterraform
code --install-extension ms-azuretools.vscode-azurevirtualmachines
code --install-extension ms-azuretools.vscode-cosmosdb
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-dotnettools.vscode-dotnet-runtime
code --install-extension ms-kubernetes-tools.vscode-kubernetes-tools
code --install-extension ms-mssql.mssql
code --install-extension ms-python.python
code --install-extension ms-vscode.azure-account
code --install-extension ms-vscode.azurecli
code --install-extension ms-vscode.vscode-node-azure-pack
code --install-extension ms-vscode.vscode-typescript-tslint-plugin
code --install-extension ms-vsliveshare.vsliveshare
code --install-extension msazurermtools.azurerm-vscode-tools
code --install-extension msjsdiag.debugger-for-chrome
code --install-extension pnp.polacode
code --install-extension pushqrdx.inline-html
code --install-extension redhat.vscode-yaml
code --install-extension RobbOwen.synthwave-vscode
code --install-extension rust-lang.rust
code --install-extension sdras.night-owl
code --install-extension silvenon.mdx
code --install-extension somekittens.hot-dog-stand
code --install-extension stackery.stackery
code --install-extension stuart.unique-window-colors
code --install-extension svelte.svelte-vscode
code --install-extension TimVaneker.serverless-snippets
code --install-extension VisualStudioExptTeam.vscodeintellicode
code --install-extension vscode-icons-team.vscode-icons
code --install-extension WallabyJs.quokka-vscode
code --install-extension whizkydee.material-palenight-theme
```