# Running Megatron

The [megatron](https://github.com/chasiotis/megatron) is PoC to deliver a kubernetes native replacement for Optimus using opensource components.

## Installing the Chart

To install the chart with the release name `megatron09`:

```bash
$ helm install systems/megatron --name megatron09 --namespace staging09 --set image.tag=1.0.0
```

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete the `megatron09` release:

```bash
$ helm delete megatron09
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration

The following table lists the configurable parameters of the `megatron` chart and their default values.

Parameter | Description | Default
--- | --- | ---
`image.tag` | Image tag | `1.0.0`
`image.pullPolicy` | Image pull policy | `IfNotPresent`
