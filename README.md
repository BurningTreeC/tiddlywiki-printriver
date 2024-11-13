# tiddlywiki-printriver

This plugin adds a Print River to [TiddlyWiki5](https://tiddlywiki.com)

Tiddlers can be opened in a dedicated new window
Titles, subtitles and tags can be shown or hidden
Various alignments and reordering can be done before printing
Finally, there's a print button to print the resulting window

# Installation

## The Drag&Drop way:

- Go to [the plugin page](https://burningtreec.github.io/tiddlywiki-printriver/)
- Drag the plugin box from the "Installation" tiddler to your wiki

## The NodeJs way:

- Clone this repository to your [TIDDLYWIKI_PLUGIN_PATH](https://tiddlywiki.com/#Environment%20Variables%20on%20Node.js)

```
git clone --depth=1 git@github.com:BurningTreeC/tiddlywiki-printriver.git $TIDDLYWIKI_PLUGIN_PATH
```

- Enable the plugin in your wiki's tiddlywiki.info file

```
"plugins": [
	"plugins/first-plugin",
	"plugins/second-plugin",
	"tiddlywiki-printriver/printriver"
	]
```
