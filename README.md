# hexo-asset-image


自动为hexo中的图片提供绝对路径

# 使用

```shell
npm install hexo-asset-image --save
```

# 例子

```shell
MacGesture2-Publish
├── apppicker.jpg
├── logo.jpg
└── rules.jpg
MacGesture2-Publish.md
```

修改`_config.yml`中的`post_asset_folder: true`

hexo new post [title] 后，会在_posts文件夹下生成同名文件夹，在需要插入图片的地方写`![logo](logo.jpg)`，将插入[title]文件夹下`logo.jpg`.

# fork自https://github.com/xcodebuild/hexo-asset-image

# 修复了bug
