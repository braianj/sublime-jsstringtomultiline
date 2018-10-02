sublime-jsstringtomultiline
===================

Based on :
[![V 1.0.0](https://img.shields.io/badge/Version_1.0.0-Stable-green.svg)](https://github.com/braianj/sublime-jsstringtomultiline/tree/v-1.0.0) |

Sublime plugin for creating multiline string from selected text in JavaScript.

This plugin will take selected text and convert it to a javascript string of lines.
For example, the following text
```
                <div class='form-group'>
                    <label for="input" class="col-sm-2 control-label">:</label>
                    <div class="col-sm-2">
                    </div>
                </div>
```
is converted to
```javascript
                    '<div class=\'form-group\'>'+
                        '<label for=\"input\" class=\"col-sm-2 control-label\">:</label>'+
                        '<div class=\"col-sm-2\">'+
                        '</div>'+
                    '</div>',
```

The default keybinding is ctrl-alt-m-l

Enjoy!

License
-------
This package is licensed under the Apache License, version 2.  See LICENSE file for details.
