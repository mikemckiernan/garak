# Documentation

## Building the Documentation

1. Build the documentation:

   ```console
   make -c docs/source doc
   ```

   The HTML is created in the `docs/source/html` directory.

## Publishing the Documentation

Tag the commit to publish with `docs-v<semver>`.

To avoid publishing the documentation as the latest, ensure the commit has `/not-latest` on a single line, tag that commit, and push to GitHub.
