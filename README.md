# tfaction-workflow

Reusable workflows for [tfaction](https://github.com/suzuki-shunsuke/tfaction)

## Workflows

* workflow_dispatch
  * [test](.github/workflows/test.yaml): Run `terraform plan` 
  * [hide-comment](.github/workflows/hide-comment.yaml): Hide old Pull Request comments
    Others
  * [update-aqua-checksums](.github/workflows/update-aqua-checksums.yaml): Update aqua-checksums.json
  * [actionlint](.github/workflows/actionlint.yaml): Lint GitHub Actions Workflows with [actionlint](https://github.com/rhysd/actionlint)
  * [apply](.github/workflows/apply.yaml): Run `terraform apply` 

