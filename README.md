# 🇺🇸 🦅 loading-attribute-eagle-polyfill
A polyfill for [`<img loading="eagle" />`](https://twitter.com/_jayphelps/status/1288701159713189888). Displays an America Eagle as the placeholder of the image while the your real images are still loading.

<img src="https://www.publicdomainpictures.net/pictures/50000/velka/bald-eagle-and-a-flag.jpg" height="300" />

## Usage

```html
<script src="https://unpkg.com/loading-attribute-eagle-polyfill/loading-attribute-eagle-polyfill.js"></script>
```
Include the polyfill in your `<head>`, then you can add the `loading="eagle"` attribute to any of your images.

```html
<head>
  <script src="https://unpkg.com/loading-attribute-eagle-polyfill/loading-attribute-eagle-polyfill.js"></script>
</head>
<body>
  <!- Here's an example URL that artificially delays the src so you can see the proud Eagle ->
  <img
    loading="eagle"
    src="https://deelay.me/2000/https://img.webmd.com/dtmcms/live/webmd/consumer_assets/site_images/article_thumbnails/other/cat_relaxing_on_patio_other/1800x1200_cat_relaxing_on_patio_other.jpg"
    width="300"
    height="200"
  />
</body>
```

## Browser Support
Yes.

## Known Issues
While you don't have to be American to use this polyfill, it currently only supports one eagle: the Great American Bald Eagle. It's not yet clear if/how developers will be able to choose different eagles, or personalize it based on locales.
