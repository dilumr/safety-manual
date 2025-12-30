# safety-manual

## Contributor Notes

### Set up environment

This project uses `uv`. So install `uv` if you don't have it already:

    > brew install uv

### Previewing content changes

The contents are in markdown files and static resources. These are all in the `./docs` directory. You can preview changes made to the content by running a local server:

    > uv run mkdocs serve

### Publishing a new version to the web

Any merge or commit to `main` branch is automatically built and published to `gh-pages` branch.
