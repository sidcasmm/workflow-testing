# workflow-testing

## PR Labeler

This repo uses [actions/labeler](https://github.com/actions/labeler) to automatically add labels to every PR targeting `main` based on which files were changed.

### One-time setup: Create labels

Create these labels in **Settings → Labels** (or they’ll be skipped):

| Label           | Color (suggestion) |
|-----------------|--------------------|
| documentation   | `#0075ca`          |
| config / ci     | `#7057ff`          |
| dependencies    | `#d876e3`          |
| source          | `#0e8a16`          |
| tests           | `#1d76db`          |

### Customization
 - Tetsing Labeler
Edit [`.github/labeler.yml`](.github/labeler.yml) to change which file patterns map to which labels.
