# Sharing something

The easy way: ElectroLab, then **Community**, then **Share…**. The app prepares everything and opens a pull request under your GitHub account.

By hand: add a folder `items/<lowercase-name>/` with `item.json`:

```json
{"title": "Box for Arduino Uno", "description": "A snap-fit box with a USB opening.", "kind": "model", "author": "your-github-name", "license": "CC-BY-4.0", "tags": ["enclosure", "uno"], "created": "2026-11-20T10:00:00Z", "files": ["model.3mf", "thumb.jpg"]}
```

`kind` is `model`, `circuit` or `both`. Circuits are `project.json` (+ `sketch.ino`). Allowed files: .stl .3mf .json .ino .jpg .png .md, each up to 25 MB. License: CC0-1.0, CC-BY-4.0, CC-BY-SA-4.0 or MIT.
