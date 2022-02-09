Documentation is automatically pushed to the `main` branch of this repository from [this Github Action](https://github.com/OpenGen/GenTL/blob/main/.github/workflows/docs.yml) in the GenTL repository.
There is a Deploy key for this repository that is stored as a Github Actions secret within the GenTL that allows that Github Action to push to this repository.
A github-pages Github Action for this repository then deploys the documentation to https://opengen.github.io/gentl-docs/latest.
