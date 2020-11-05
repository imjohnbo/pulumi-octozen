# Pulumi Octozen

Playground for managing static website infrastructure on Azure through [Pulumi](https://pulumi.com).

## Usage

On a pull request, the [`Pull Request`](https://github.com/imjohnbo/pulumi-octozen/blob/master/.github/workflows/pr.yml) workflow runs `pulumi preview`.

On a merge to the default branch, the [`Push`](https://github.com/imjohnbo/pulumi-octozen/blob/master/.github/workflows/push.yml) workflow runs `pulumi up`.

## Resources
- https://github.com/pulumi/examples/tree/master/azure-ts-static-website