# Smarty Sugar for Espresso

Smarty is a PHP Template Engine for designers. Built in LiveStreet and CoGear.
I hate any template engine but use it every day in developing LS skin and skin Sugar is a working solution for Smarty syntax (.tpl files, for example).
Based on the [php-smarty TextMate bundle](https://github.com/textmate/php-smarty.tmbundle) and forked from [prtm](https://github.com/ptrm/)'s repo.

## Known bugs
- smarty highlighting is present inside html tags enclosed by `{literal}`
- custom block functions (e.g. `{textformat}{/textformat}`) won't show in itemizer as a parent node

## Todo
- highlighting for `$smarty` reserved variable and foreach/section variables (`index`, `iteration` etc.)
- auto-completion and highlighting for native variable modifiers
- mark invalid syntax?
Note: it's prtm's TODO, not My (Grawl's)

## Copying
	Permission to copy, use, modify, sell and distribute this
	software is granted. This software is provided "as is" without
	express or implied warranty, and with no claim as to its
	suitability for any purpose.
