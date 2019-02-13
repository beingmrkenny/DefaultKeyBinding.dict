# DefaultKeyBinding.dict

## Key Bindings

* Makes typing curly quotes more gooder
* Changes cursor malarkey

| Key Sequence | Character / Action |
|--------------|---------------|
| `⌥ + [` | ‘ |
| `⌥ + ]` | ’ |
| `⇧ + ⌥ + [` | “ |
| `⇧ + ⌥ + ]` | ” |
| `↖ Home`<br> (`fn + ←`)  | move cursor to beginning of line |
| `↘ End`<br>  (`fn + →`) | move cursor to end of line |
| `⇧ + ↖ Home`<br> (`⇧ + fn + ←`) | move cursor to beginning of line and select all text along the way |
| `⇧ + ↘ End`<br> (`⇧ + fn + →`) | move cursor to end of line and select all text along the way |
| `⇞ Page Up`<br> (`fn + ↑`) | page up |
| `⇟ Page Down`<br> (`fn + ↓`) | page down |

## Microsoft Designer Keyboard bundle

Also a keyboard bundle to make the characters printed on the keycaps match up with what comes out when you press them. (Apart from the ¬ character and the ¦ character, because I couldn’t get them to work and who cares anyway, nobody uses them).

## Installation

Move the .dict file so that it ends up at `~/Library/KeyBindings/DefaultKeyBinding.dict`

Copy the .bundle **directory** so that it ends up at `~/Library/Keyboard\ Layouts/MSDesignerKeyboard.bundle`

## Syntax

`"[keycombination]" = ("insertText:", "&#092;[unicodenumber or actual character]");`

	Prefix   Meaning
	~        ⌥ option key
	$        ⇧ shift key
	^        ^ control key
	@        ⌘ command key
	#        Keys on number pad

More information about keybinding syntax:
http://xahlee.info/kbd/osx_keybinding_key_syntax.html

Not familiar with coding or need more complex keybinding modifications? Try this:
http://scripts.sil.org/ukelele

## Authors

**Tunghsiao Liu (original author)**

+ http://twitter.com/tunghsiao
+ http://github.com/sparanoid

**Mark Kenny**

+ https://beingmrkenny.co.uk/
+ http://github.com/beingmrkenny
