# sognix's Unraid templates

Community Applications repository of sognix: the templates that make these projects
installable from the Unraid **Apps** tab. The code, images and plugin files live in the
project repositories; the templates here only point to them.

| Name | Type | Template | Project and support |
|---|---|---|---|
| Video2X WebGUI | Docker | [templates/video2x-webgui.xml](templates/video2x-webgui.xml) | [sognix/video2x-webgui](https://github.com/sognix/video2x-webgui) |
| Swap Manager | Plugin | [plugins/swap-manager.xml](plugins/swap-manager.xml) | [sognix/unraid-swap-manager](https://github.com/sognix/unraid-swap-manager) |

Please report problems in the issues of the project repository, not here.

## Maintainer notes

- `templates/video2x-webgui.xml` is a copy of `unraid/video2x-webgui.xml` in the
  video2x-webgui repository. That file stays there: its `TemplateURL` points to it, and
  installed containers use that URL. Change both copies together.
- The plugin template's `PluginURL` must match the `pluginURL` in the plugin's `.plg` exactly.
- After every template change: Validate and Scan on https://ca.unraid.net/submit.

## License

The templates and metadata in this repository are MIT licensed, see [LICENSE](LICENSE).
The projects themselves have their own licenses.
