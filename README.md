# proto-toml-plugins

TOML plugins for moonrepo/proto

## About

Just a small collection of TOML plugins for the [moonrepo/proto](https://github.com/moonrepo/proto) tool.
See the [Moonrepo Plugins](https://moonrepo.dev/docs/proto/plugins) pages for more information about how to
create your own TOML/WASM plugins.

## Installation Methods

The plugins can be installed via `proto` itself. Assuming you wanted to install the latest available `gojq`:

```
proto add-plugin gojq "source:https://raw.githubusercontent.com/stk0vrfl0w/proto-toml-plugins/main/plugins/gojq.toml"
proto install gojq
```

Refer to https://moonrepo.dev/docs/proto/tools#third-party for more information.

## Available plugins in this repo

* buf - Protocol Buffers (https://github.com/bufbuild/buf)
* gojq - Go Implementation of jq (https://github.com/itchyny/gojq)
* helm - Kubernetes Package Manager (https://github.com/helm/helm)
* helmfile - Helm Chart Deployments (https://github.com/helmfile/helmfile)
* kubectl - Kubernetes CLI Tool (https://github.com/kubernetes/kubectl)
* sops - Secrets Operations (https://github.com/getsops/sops)
* terragrunt - Terraform wrapper (https://github.com/gruntwork-io/terragrunt)
* zig - Zig language & toolchain (https://github.com/ziglang/zig)
