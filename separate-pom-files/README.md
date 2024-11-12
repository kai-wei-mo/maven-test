https://stackoverflow.com/a/53377399

This solution involves creating a separate POM file for dependencies that pull from different repository. It allows you to keep the repositories separate from the main POM file. Dependencies can only be resolved from the repositories defined in their respective POM files.

By running `make cleancache && make compile`, you can see that the dependencies are resolved from the repositories defined in their respective POM files.
