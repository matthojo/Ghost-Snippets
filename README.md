# Ghost Snippets

A Sublime plugin for [Ghost](http://ghost.org) snippets.

## Install
### Using Package Control:

* Bring up the Command Palette (Command+Shift+P on OS X, Control+Shift+P on Linux/Windows).
* Select Package Control: Install Package.
* Search Ghost
* Select Ghost Snippets to install.

### Not using Package Control:

* Save files to the `Packages/Ghost Snippets` directory, then relaunch Sublime:
* Linux: `~/.config/sublime-text-3/Packages/Ghost Snippets`
* Mac: `~/Library/Application Support/Sublime Text 3/Packages/Ghost Snippets`
* Windows: `%APPDATA%/Sublime Text 3/Packages/Ghost Snippets`
* 
## Available Snippets
### Theming

* author → `{{author}}`
* author.b → `{{author.bio}}`
* author.c → `{{author.cover}}`
* author.e → `{{author.email}}`
* author.i → `{{author.image}}`
* author.n → `{{author.name}}`
* author.w → `{{author.website}}`

* body → `{{body}}`
* foot → `{{ghost_foot}}`
* head → `{{ghost_head}}`
* meta_desc → `{{meta_description}}`
* meta_t → `{{meta_title}}`

* blog_desc → `{{@blog.description}}`
* blog_logo → `{{@blog.logo}}`
* blog_title → `{{@blog.title}}`
* blog_url → `{{@blog.url}}`

* bodyclass → `{{body_class}}`
* postclass → `{{post_class}}`

* foreach → `{{#foreach }}{{/foreach}}`
* @odd → `{{#if @odd}} {{/if}}`
* @even → `{{#if @even}} {{/if}}`
* @first → `{{#if @first}} {{/if}}`
* @last → `{{#if @last}} {{/if}}`
* @rowStart → `{{#if @rowStart}} {{/if}}`
* @rowEnd → `{{#if @rowEnd}} {{/if}}`

* content → `{{content}}`
* date → `{{date format=""}}`
* excerpt → `{{excerpt}}`
* pagin → `{{pagination}}`
* tag.n → `{{tag.name}}`
* tags → `{{tags}}`
* title → `{{{title}}}`
* url → `{{url absolute=""}}`

## Copyright & License

Copyright (C) 2013 The Ghost Foundation - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
