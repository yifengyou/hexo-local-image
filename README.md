# hexo-local-image


Give local image in hexo a relative path automatically

# Usege

```shell
npm install hexo-local-image --save
```

# Example

```shell
MacGesture2-Publish
├── apppicker.jpg
├── image.jpg
└── rules.jpg
MacGesture2-Publish.md
```

Make sure `post_asset_folder: true` in your `_config.yml`.

Just use `![logo](${MDFileName}/image.jpg)` to insert `image.jpg`.

# History

* 2019-09-09: support hexo-relativelink
