# sandbox-build

This is a test repository for using GitHub actions to build containers and to store those in a package.

After building the Apptainer container from the definition file, you can download and run it using

    apptainer pull oras://ghcr.io/robertoostenveld/sandbox-build:latest
    apptainer run sandbox-build_latest.sif

or without saving it locally

    apptainer run oras://ghcr.io/robertoostenveld/sandbox-build:latest

## See also

- https://apptainer.org/docs/user/latest/cli.html
- https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/accessing-contextual-information-about-workflow-runs#github-context
- https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/store-information-in-variables