[Exporting the extension list in VS Code](https://stackoverflow.com/questions/35773299/how-can-you-export-vs-code-extension-list)

```bash
# Run the command on the machine you want to backup
code --list-extensions | xargs -L 1 echo code --install-extension

## Sample output 
code --install-extension bungcip.better-toml
code --install-extension burkeholland.simple-react-snippets
code --install-extension christian-kohler.npm-intellisense
code --install-extension christian-kohler.path-intellisense
code --install-extension CoenraadS.bracket-pair-colorizer-2
code --install-extension dbaeumer.vscode-eslint
code --install-extension dsznajder.es7-react-js-snippets
code --install-extension eamodio.gitlens
code --install-extension Equinusocio.vsc-material-theme
code --install-extension gencer.html-slim-scss-css-class-completion
code --install-extension jpoissonnier.vscode-styled-components
code --install-extension kisstkondoros.csstriggers
code --install-extension ms-vscode.Go
code --install-extension ms-vsliveshare.vsliveshare
code --install-extension msjsdiag.debugger-for-chrome
code --install-extension remimarsal.prettier-now
code --install-extension ritwickdey.LiveServer
code --install-extension robertohuertasm.vscode-icons
code --install-extension rust-lang.rust
code --install-extension sdras.night-owl
code --install-extension whizkydee.material-palenight-theme
```