# Minimal repro for rg/node performance issue with VSCode remote containers
https://github.com/microsoft/vscode-remote-release/issues/369

This is a clone of https://github.com/microsoft/vscode-dev-containers/tree/master/containers/dotnetcore-2.1 plus switching to docker-compose.

To reproduce, open the remote workspace and wait.  You can monitor it by opening a terminal and running `top`:
![top](https://i.imgur.com/3VlRzgv.png)