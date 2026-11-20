# ZotLit Reader

Read the PDFs of your Obsidian vault in the ZotLit PDF Reader.

- Open each PDF of the vault in the reader: in a tab, in an embed, in a hover preview and in a canvas card.
- Link to a selection of text and go back to it from your notes.
- Use the reader without Zotero and without the ZotLit plugin.

ZotLit Reader is in beta. Install it with [BRAT](https://github.com/TfTHacker/obsidian42-brat) from `aidenlx/zotlit-reader`.

The source code is in [aidenlx/zotlit-repo](https://github.com/aidenlx/zotlit-repo), under `apps/reader`.

## About this repository

This repository publishes ZotLit Reader: its releases, and the Resource Releases
(`res-<version>`) that the plugin downloads at runtime. Its tree builds the
plugin from the npm package
[`@zotlit/reader-plugin`](https://www.npmjs.com/package/@zotlit/reader-plugin)
at the version that `package.json` names: `pnpm install`, then
`pnpm run build` writes `main.js` and `styles.css`. The source code, the
issue tracker and the development history are in
[aidenlx/zotlit-repo](https://github.com/aidenlx/zotlit-repo). This tree is
generated at each release: send changes to the source repository.

