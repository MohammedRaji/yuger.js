![yuger.js Logo]()
# yuger.js
yuger.js is a JavaScript library which can be used to add highly customizable vibrant icons to the DOM without any dependencies.



### Check [DEMO](https://webkul.github.io/vivid/docs.html)

---

## Introduction
`yuger.js`  is an SVG Icons library which can be used to add SVG icons to the DOM without any dependencies.

`yuger.js` is custumazible library, so can be modify existid icon or add other icon easyly.

## Getting Started
To get started with yuger.js, you just need to include **`yuger.js`** to your project.

```html
<script src="yuger.js" type="text/javascript"></script>
```
### Using an Icon
An SVG Icon can be easily included using the syntax `<i data-icon="icon-name"></i>` , where **`icon-name`** is replaced by the unique name of the respective icon.

### Example Code
```html
<i data-icon="yf-facebook"></i>
```

![facebook logo]()

### Customizing Icon Size
To customize the size of the respective icon, Add `data-ratio="number"` data attribute to `i` element to customize size of the icon.

> yuger.js icon has 20px*20px initial dimention, `data-ratio="2"` for exampale means initial dimenton multiple by 2, as well give us 40px*40px dimention
#### Example Code
```html
<i data-icon="yf-facebook" data-ratio="2"></i>
```

### Customizing Icon Color
To customize the color of specifice icon, you can customize it using CSS code like that:
```CSS
[data-icon=icon-name] {
    fill: red;
}
```
#### Example Code
```CSS
[data-icon=yf-twitter] {
    fill: red;
}
```
### Voila! You're done
Once the compilation process is over, your browser will fire up to show the compiled Vivid SVG Icons in your browser from the `./dist/preview.html` file.

## Adding Icons
If you wish to create your very own yuger.js with your custom icons, just add the name and SVG code of your icon to `iconObject` in yuger.js code.


## Contributing

> **Note:** In order to ensure the quality of each icon, we currently do not accept third-party drawn icons. If you want to contribute an icon to Remix Icon, you can create an [issue](https://github.com/Remix-Design/remixicon/issues) with a screenshot or url to your svg-format file. If you are not familiar with github, you can also email us directly `jimmy@remixdesign.cn`.

### Icon Request

If there is no suitable icon for your usage scenario, you can create an [issue](https://github.com/Remix-Design/remixicon/issues) with a title of "Icon request: <Icon name>" and fill the issue template.

> RemixIcon is mainly focuses on user interface icons. If we did not include the logo icons you were looking for, I recommend this icon library - [Simple Icons](https://github.com/simple-icons/simple-icons)


## License

**yuger.js** is licensed under the [MIT](LICENSE).  Feel free to use this library in your products and distribute them. The only thing we ask is that mention `yuger.js` in your product info.
