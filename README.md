# List-bare

The `list-bare` object simply removes bullets and indents from lists.

## Dependencies

The List bare module depends on one other module:

* [settings.defaults](https://github.com/treeframework/settings.defaults)

If you install the `list-bare` module using Bower or npm, you will get these 
dependencies at the same time. If not using Bower or npm, please be sure to 
install and `@import` these dependencies in the relevant way.

## Installation

You can install the `list-bare` module via npm, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-list-bare --save
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "bower_components/tree-list-bare/object.list-bare";
```

### Install using npm:

```sh
$ npm install tree-list-bare --save
```

### Install via file download

The least recommended option for installation is to simply download
`_object.list-bare.scss` into your project and `@import` it into your project in
its Object layer.

## Usage

Basic usage of the List-bare module uses the required classes:

```html
<ul class="o-list-bare">
    <li>Foo</li>
    <li>Bar</li>
    <li>Baz</li>
</ul>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
