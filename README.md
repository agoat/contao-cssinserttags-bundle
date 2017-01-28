# CSS Insert tags to include (resized) images in stylesheets
Insert tags for style sheets

## Install:


--
## Usage:
### To use resized image as an asset
```css
.class {
    background: url({{image::imageUUID?width=100&height=100&mode=crop}}) #fff;
}
```

### To embed resized image
```css
.class {
    background: url({{embed::imageUUID?width=100&height=100&mode=crop}}) #fff;
}
```

*under heavy development (do not use)*
