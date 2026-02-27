# boilersync-workspace

## Getting started

This repo is a [multi](https://github.com/montaguegabe/multi) workspace to manage multiple sub-repositories:

- [boilersync-cli](https://github.com/montaguegabe/boilersync)
- [boilersync-desktop](https://github.com/montaguegabe/boilersync-desktop)
- [boilersync-skills](https://github.com/montaguegabe/boilersync-skills)

To get started, install multi with `pipx install multi-workspace` or `uv tool install multi-workspace`.

Then install the [extension](https://marketplace.visualstudio.com/items?itemName=montaguegabe.multi-workspace) in Cursor or VS Code. When you make new changes to the VS Code configurations or other sync config files in a sub-repo, the changes will be automatically synced to the workspace.

## BoilerSync Skill Installation

Install the BoilerSync template skill with `vercel-labs/skills`:

```bash
npx skills add montaguegabe/boilersync-skills --skill boilersync-template
```
