# GitOps repository sample for FluxCD

This projects is a GitOps repository sample for FluxCD.
Use this sample to deploy cluster-wide services and apps to your clusters the GitOps way.

Check out [github.com/alexandreroman/fluxcd-with-tanzu](https://github.com/alexandreroman/fluxcd-with-tanzu)
to see how to set up FluxCD with Tanzu, so that every Kubernetes cluster you create
would use the same GitOps repo at scale.

Entry point for this repo is under directory `clusters`: the FluxCD configuration
expects to find a file named after your cluster name (with the `.yaml` extension),
containing a [FluxCD Kustomization](https://fluxcd.io/docs/components/kustomize/kustomization/)
definition.

## Contribute

Contributions are always welcome!

Feel free to open issues & send PR.

## License

Copyright &copy; 2022 [VMware, Inc. or its affiliates](https://vmware.com).

This project is licensed under the [Apache Software License version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
