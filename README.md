# Snohio Github-workflows repository

## Markdown lint

The reusable Markdown workflow runs `mdl` 0.18.1 against all `.md` files when
a Markdown file is added or modified. It supports pull requests and pushes and
uses the calling repository's `.mdlrc` configuration, if present.

## JSON lint

The reusable JSON workflow runs `demjson3` 3.0.6 against all `.json` files
when a JSON file is added or modified. It supports pull requests and pushes.

## YAML lint

The reusable YAML workflow runs `yaml-lint` 0.1.2 against all `.yml` and
`.yaml` files when a YAML file is added or modified.

## Cookstyle lint

The reusable Cookstyle workflow runs Cookstyle 9.0.9 across the repository
when a Ruby file is added or modified. It uses the calling repository's
`.rubocop.yml` configuration, if present.
