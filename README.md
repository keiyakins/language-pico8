pico-8 support in Atom
======

Add syntax highlighting and snippets to pico-8 files in Atom.

Common snippets
---
| Trigger       | Name                     | Body                 |
| ------------- |--------------------------| ---------------------|
| -[            | multiline comment        | --[[ comment... ]]   |
| =[            | nested multiline comment | --[=[ comment... ]=] |
| afun          | anon function            | functionName = function (args) -- body... end |
| for           | for i=1,10               | for i = 1, 10 do -- body... end |
| forp          | for k,v in pairs()       | for k,v in pairs(table_name) do -- body... end |
| fun           | function                 | function functionName (args) -- body... end |
| if            | if conditional           | if value then --body... end |
| ife           | if else conditional      | if value then --body... else --body... end |
| ifn           | if not conditional       | if not value then --body... end |
| ifne          | if not else conditional  | if not value then --body... else --body... end |
| lfun          | local function           | local function functionName (args) -- body... end |
| loc           | local variable definition shortcut | local x = 1 |
| local         | local variable definition | local x = 1 |
| ltab          | local table definition   | local name = {}      |
| print         | print                    | print("logging")     |
| rep           | repeat loop shortcut     | repeat -- body... until condition |
| repeat        | repeat loop              | repeat -- body... until condition |
| req           | require shortcut         | local name = require "module" |
| require       | require                  | local name = require "module" |
| ret           | return definition shortcut | return value       |
| return        | return definition        | return value         |
| tab           | table definition         | name = {}            |
| whi           | while loop shortcut      | while condition do -- body... end |
| while         | while loop               | while condition do -- body... end |


Contributors
------------

* Maintainer: __Tobias V. Langhoff__ ([https://github.com/tobiasvl](https://github.com/tobiasvl))
* Original author: __Keiya Bachhuber__ ([https://github.com/keiyakins](https://github.com/keiyakins))
* Based heavily on [Jorge Garrido Oval](https://github.com/FireZenk)'s [language-lua](https://github.com/FireZenk/language-lua) package                                                                                              
* Originally [converted](http://atom.io/docs/latest/converting-a-text-mate-bundle) from the [Lua TextMate bundle](https://github.com/textmate/lua.tmbundle)

Contributions are greatly appreciated. Please fork this repository and open a
pull request to add snippets, make grammar tweaks, etc.

License
------

This package is released under the MIT license.
