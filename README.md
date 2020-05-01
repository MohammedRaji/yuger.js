# yuger.js
yuger.js is a JavaScript library which can be used to add highly customizable vibrant icons to the DOM without any dependencies.


![Vivid.JS Logo](https://webkul.github.io/vivid/assets/res/vivid-logo.svg)
### Check [Beautiful Doc](https://webkul.github.io/vivid/docs.html) on Website.

---

# Introduction
Yuger.js  is an SVG Icons library which can be used to add SVG icons to the DOM without any dependencies.

Yuger.js is custumazible library, so can be modify existid icon or add other icon easyly.

# Getting Started
To get started with Vivid.JS, you just need to include `yuger.min.js` to your project.

```html
<script src="yuger.min.js" type="text/javascript"></script>
```

# Usage
Including icons with yuger.js is very easy.

## Using an Icon
An SVG Icon can be easily included using the syntax `<i data-icon="icon-name"></i>` , where `icon-name` is replaced by the unique name of the respective icon.

### Example Code
```html
<i data-vi="doc"></i>
```

## Customizing Icon Size
To customize the size of the respective icon, Add `data-vi-ratio="number"` data attribute to `i` element to customize size of the icon.

### Example Code
```html
<i data-vi="doc" data-ratio="96"></i>
```

# Icon Customization
Oh! Yes, You can customize the default size and colors of the `Vivid.JS` SVG Icons Library.

### Voila! You're done
Once the compilation process is over, your browser will fire up to show the compiled Vivid SVG Icons in your browser from the `./dist/preview.html` file.

**If you are using Windows environment replace the `"open-html": "open ./dist/preview.html"` with `"open-html": "show ./dist/preview.html"` in `package.json` file.**

# Adding Icons
If you wish to create your very own Vivid.JS with your custom icons, Follow the steps below -

Once you have [installed Vivid.JS](#install-vividjs-package), `add/replace/remove` the icons from `./icons` directory

Make sure the SVG Icons which has been added must have `vi-primary` and `vi-accent` class to the respective [SVG Elements](https://developer.mozilla.org/en-US/docs/Web/SVG/Element), so that the colors can be customized later from `src/config.js`.


## Contributing

> **Note:** In order to ensure the quality of each icon, we currently do not accept third-party drawn icons. If you want to contribute an icon to Remix Icon, you can create an [issue](https://github.com/Remix-Design/remixicon/issues) with a screenshot or url to your svg-format file. If you are not familiar with github, you can also email us directly `jimmy@remixdesign.cn`.

### Icon Request

If there is no suitable icon for your usage scenario, you can create an [issue](https://github.com/Remix-Design/remixicon/issues) with a title of "Icon request: <Icon name>" and fill the issue template.

> RemixIcon is mainly focuses on user interface icons. If we did not include the logo icons you were looking for, I recommend this icon library - [Simple Icons](https://github.com/simple-icons/simple-icons)


## License

Remix Icon is licensed under the [MIT](LICENSE).  Feel free to use this library in your products and distribute them. The only thing we ask is that mention `yuger.js` in your product info.
