# orgmode octopress pack

An [emacs-live](https://github.com/overtone/emacs-live) pack containing utility functions to write in org-mode and export to octopress
in Markdown for publishing.

This Org-mode Octopress packages is taken(stolen?) from [https://github.com/yoshinari-nomura/org-octopress](https://github.com/yoshinari-nomura/org-octopress)
and modified to export in Markdown.

## Installing and loading the pack

First clone or add submodule org-octopress-pack into a folder (for example `~/.live-packs/org-octopress-pack`).

Then create a `~/.emacs-live.el` file and use the function `live-add-packs` to load the org-octopress-pack:

    (live-add-packs '(~/.live-packs/org-octopress-pack))
