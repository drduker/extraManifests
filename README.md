## How to use

# extra-manifests

A tiny chart to add just extra manifests

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| extraManifests | list | `[]` | Add any number of kubernetes resources |

## How to update docs dynamically
```docker run --rm --volume "$(pwd):/helm-docs" -u $(id -u) jnorwood/helm-docs:latest```
