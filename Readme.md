
# table

Full featured tables

## Installation

Install with [component](http://component.io):

    $ component install chameleonui/table

## API

### Variables

You can change look and feel via following variables:

```
grid-columns-count = 12;

table-border-radius = 5px;
table-cell-padding = 8px;
table-condensed-cell-padding = 4px;
table-border-color = #aaa;
table-color = #000;
table-bg-color = #fff;

table-hover-color = inherit;
table-hover-bg-color = #e1e1e1;

table-caption-color = #000;

table-thead-bg-color = transparent;
table-thead-color = table-color;

table-tr-even-bg-color = table-bg-color; //use rgba if you want to style cols
table-tr-even-color = table-color;
table-tr-odd-bg-color = #f1f1f1; //use rgba if you want to style cols
table-tr-odd-color = table-color;

table-tfoot-bg-color = transparent;
table-tfoot-color = table-color;
```

### Use flags

You can disable some table feature through use-flags:

```
use-table-style = true|false;
use-table-condensed = true|false;
use-table-striped = true|false;
use-table-bordered = true|false;
use-table-hover = true|false;
```

### Init

```
table();
```

## Author(s)

Edgedesign s.r.o. – Tomas Kuba

## License

The MIT License (MIT)

Copyright © 2013 Edgedesign s.r.o.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.