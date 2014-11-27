# Roon

The Roon theme for [Ghost](http://github.com/tryghost/ghost/).

To download, visit the [releases](https://github.com/TryGhost/Roon/releases) page.

## Font Options

This theme comes with two font options; a serif and sans-serif. Switching between them must be done in the HTML, by changing a `class` on the `<body>` element in [default.hbs](https://github.com/TryGhost/Roon/blob/master/default.hbs#L23).

**Sans-Serif - Gibson**

The sans-serif is the default, so you don't need to add anything. The `<body>` element should look like this:

```html
<body class="{{body_class}} {{#is 'index, tag, author'}}user{{/is}} {{#is 'post'}}{{#unless post.image}}noimage{{/unless}}{{/is}}">
```

**Serif - Filo Pro**

For the serif font, the `<body>` element should look like this:

```html
<body class="serif {{body_class}} {{#is 'index, tag, author'}}user{{/is}} {{#is 'post'}}{{#unless post.image}}noimage{{/unless}}{{/is}}">
```

## Colour Options

This theme uses an accent colour for links and the border at the top of pages.

To change this colour, you need to edit [assets/css/screen.css](https://github.com/TryGhost/Roon/blob/master/assets/css/screen.css).

There are only two values you need to change, conveniently **located at the very top of the file**.

## Copyright & License

Copyright (c) 2013-2014 Sam Soffes & Ghost Foundation.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
