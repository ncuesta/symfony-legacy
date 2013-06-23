# symfony-legacy

Create new symfony 1.4 projects easily with Composer.

## What's included?

This package includes a predefined set of plugins that I find myself using in
every symfony project I start. Feel free to fork it and customized it to fit
*your* needs.

Bundled plugins:

* **sfPropelORMPlugin**
* **dcReferenceModelPlugin**
* **dcReloadedFormExtraPlugin**

## Usage

1. Get [Composer](http://getcomposer.org).
2. Create a project using this installer:

```bash
$ composer create-project ncuesta/symfony-legacy path/to/your/hawt/project
$ cd path/to/your/hawt/project
$ php bin/symfony generate:project HawtnessProject
```

**This rather hacky way to start the project will be automated and improved soon.**

## License

This project is distributed under the MIT license. Legal stuff to follow.

```
Copyright (c) 2013 José Nahuel Cuesta Luengo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
