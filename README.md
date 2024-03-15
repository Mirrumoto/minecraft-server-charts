# minecraft-server-charts

[![](https://github.com/mirrumoto/minecraft-server-charts/workflows/Release%20Charts/badge.svg?branch=master)](https://github.com/mirrumoto/minecraft-server-charts/actions)

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add mirrumoto https://mirrumoto.github.io/minecraft-server-charts/
```

You can then run `helm search repo itzg` to see the charts.

## Charts

* [mc-router](https://github.com/mirrumoto/minecraft-server-charts/tree/master/charts/mc-router)
* [minecraft](https://github.com/mirrumoto/minecraft-server-charts/tree/master/charts/minecraft)
* [minecraft-bedrock](https://github.com/mirrumoto/minecraft-server-charts/tree/master/charts/minecraft-bedrock)
* [minecraft-proxy](https://github.com/mirrumoto/minecraft-server-charts/tree/master/charts/minecraft-proxy)
* [rcon-web-admin](https://github.com/mirrumoto/minecraft-server-charts/tree/master/charts/rcon-web-admin)

```bash
helm install --name your-release mirrumoto/minecraft
```
