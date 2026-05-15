# MuxCore Official Marketplace

This is the official module catalog for MuxCore. Add this repository URL to your MuxCore instance to discover official modules.

## URL

```
https://github.com/Muxcore-Media/marketplace-catalog
```

## For Third-Party Marketplaces

Anyone can create a marketplace catalog. Create a repo with a `catalog.json` file listing module repo URLs. Users add your repo URL to their MuxCore instance.

## Module Repo Requirements

Each module repo must have a `muxcore.json` at its root with:

```json
{
  "name": "Module Name",
  "description": "What it does",
  "version": "1.0.0",
  "icon": "https://...",
  "author": "Author Name",
  "kind": "downloader",
  "capabilities": ["downloader.torrent"],
  "dependencies": [],
  "homepage": "https://github.com/org/repo"
}
```
