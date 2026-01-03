# larsfeddern.github.com

This repository contains my Github Pages content.  

## linktree

This repository contains the source code for my personal linktree website, which can be found at [larsfeddern.github.io](https://larsfeddern.github.io) and [larsfeddern.com](https://larsfeddern.com).

## docs

This directory is used for Github Pages to show content on larsfeddern.com that redirects to larsfeddern.github.io
If there is a new version available in /linktree/dist that gets compiled by `running bin run build`, copy the created files to /docs
and commit the changes to Github. Github Pages will automatically update the content on larsfeddern.com
to reflect the changes made in /docs.

To build the project, run:

```bash
bin/run build
```

To serve the project locally, run:

```bash
bin/run serve
```

For more information, visit the main repository at /linktree
