# Ember-cli-cropper

This is npm package for ember-cli-cropper(https://github.com/fengyuanchen/cropper) addon.

## Installation

* `npm install --save-dev ember-cli-cropper`
* `ember g ember-cli-cropper`

## Usage
 In your handlebars templates:
```
{{ember-cli-cropper source=imageSource crossorigin=true options='{"aspectRatio": 1,"minContainerWidth": 400,"minContainerHeight": 300, "minCropBoxWidth": 150, "minCropBoxHeight": 150}' }}

```

Methods calls:

```
Ember.$('.img-container > img').cropper('rotate', 90);
```
