# yuger.js
yuger.js is a JavaScript library which can be used to add highly customizable vibrant icons to the DOM without any dependencies.

### Check [DEMO](https://mohammedraji.github.io/yuger.js/)

---

## Introduction
`yuger.js` is the SVG Icons library that can be used to add SVG icons to the DOM without any dependencies, and it is a customizable library so that it can be modified in an existing icon or easily add other icons.

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

### Customizing Icon Size
To customize the size of the respective icon, Add `data-ratio="number"` data attribute to `i` element to customize the size of the icon.

> yuger.js icon has 20px*20px initial dimention, `data-ratio="2"` for example means initial dimension multiply by 2, so give us 40px*40px dimention

#### Example Code
```html
<i data-icon="yf-facebook" data-ratio="2"></i>
```

### Customizing Icon Color
To customize the color of the specific icon, you can customize it using CSS code like that:

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

## Adding Icons
If you wish to create your very own yuger.js with your custom icons, just add the name and SVG code of your icon to `iconObject` in yuger.js code.

## Contributing

* Create an [issue](https://github.com/MohammedRaji/yuger.js/issues/new) with your feedback, idea, request etc.
* [Fork](https://github.com/MohammedRaji/yuger.js/fork) me and contribute with improved/new icons :)

>**Note:** we currently do not accept third-party drawn icons. 

## License

**yuger.js** is licensed under the [MIT](LICENSE).  Feel free to use this library in your products and distribute them. The only thing we ask is that mention `yuger.js` in your product info.
