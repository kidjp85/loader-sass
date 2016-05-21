loading-spinner-sass
=======================

> This Sass Mixin Libs is based on the great library created by Luke Haas, which can be found [HERE](http://projects.lukehaas.me/css-loaders/)

## Usage
There are 8 types of Single Element CSS Spinners (loader1~8).
Spinner's size, font-size, color are can easily changed by setting the input params.

> DEFAULT STYLE

**For .sass file**
```css
.loader-icon
  +loader1  //Default params for loader1($iconSize: 1em, $fontSize: 1em, $foregroundColor: #ef6c00, $time: 1s)
```


**For .scss file**

```css
.loader-icon {
    @include loader1
}
```

> CUSTOMIZED STYLE

```css
.loader-icon
  +loader1(2em, 2em, #ccc, .9s)
```


**For .scss file**

```css
.loader-icon {
    @include loader1(2em, 2em, #ccc, .9s)
}
```

## License
MIT