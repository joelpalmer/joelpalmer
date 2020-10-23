![Neovim](https://img.shields.io/badge/editor-Neovim-green?logo=neovim&style=plastic)
## Vim is awesome
### Here is just a short list of motions and commands that are beyond the basics and very useful...
<details>
  <summary>Expand to see the list</summary>
<!--
**joelpalmer/joelpalmer** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
	
### Indenting
---------
- normal indent 5 lines: `5>>` ← FYI `ysiw` or with a W
- visual block: `Vjj>`
- Curlies: `>%` from the brace
- Paste and be aligned in new location: `]p` as opposed to just `p`
- Indent a range of line in ex: `:4,8>` 
- Indent with markers `ma` where to start `>'a` where to end
- Indent to line num: `>12gg` 
- Indent paragraph: `>}`
- Indent to top of screen: `>H`
- Indent everything: `gg=G`

### Motions
------
- `H`, `L`, `M`  → Go to High(top), Low(bottom), Middle of page

### Scroll
------
- <kbd>Ctrl</kbd> + <kbd>d</kbd> - move half screen down
- <kbd>Ctrl</kbd> + <kbd>u</kbd> - move half screen up
- <kbd>Ctrl</kbd> + <kbd>y</kbd> - move down one line
- <kbd>Ctrl</kbd> + <kbd>e</kbd> - move up one line

### Ex
---
Duplicate/move lines:
- `:t.` - duplicate line
- `:t 7` - copy it after line 7
- `:v/foo/m$` - moves not matching lines to EOF!

Other:
- `:w anotherfilename` is "saveas "
    - substitute filename with some cmd and buffer will go out to it - `:w !cat`
- `:earlier` -- go back in to by mins 15m and get back by :later
- `:.!` date or whatever command to have it dumped in to your window- the . is key
		- similar to :r! but r opens a new line and . overwrites current line!!
		- date (or whatever cmd on a line) and then run !$sh
- :arga -- add multiple files unlike with e
- :tab sball -- open buffers in tabs then use gt and gT
- :%TOhtml - creates an html page of your buffer
- :v/PATTERN/d -- delete lines that don't match pattern
- :e %:h/<filename> to create file in same directory 

### More stuff
---
- ' for mark line and backtick for exact location!
- . is current line and $ is last like in : commands
- * next occurence of word under curson
- s delete and insert like x + i
- B and E for space separated words
- '.  -- last edited line!!!
- g; -- last edit position!
- I -- insert at beginning of line
- ctrl-a -- increment- ADD!
- . -- repeat last command
- <kbd>ctrl</kbd> + <kbd>r</kbd> + whatever in command mode or insert 
	- % -- go to matching brace
	- . -- last inserted text
- q: -- command window history!
- mC and mT for code and test and then 'C and 'T
- registers -- "kyy and then "kp to paste it
- 0 register only gets populated with yanked text, not deleted. Handy for copy, delete, replace etc.
- 1 register holds last delete or change, see last bullet
	- 1-9 hold the last deletes 
  - . register has last inserted text no matter how it was inserted
- qm -- record macro under arbitrary m register
- xp: -- swap char with next char
- + to go to start of next line or first non blank character
- g+ and g- go back and forward in time
- `dab` and `daB` for delete around brackets and parens
- dt<kbd>space</kbd> and ct<kbd>space</kbd> -- delete or change up to space!!! or just dW cW!
- de -- delete everything til the end of the word and then . to repeat
- ci -- change in
- C -- just like D put puts you in insert mode
- ddp -- move current line down a row - it swaps with below line
- xp -- swap current char with next
- <kbd>ctrl</kbd> + <<kbd>f</kbd> forward a page and ctrl-b backward a page
- zt or z<kbd>return</kbd> and zb make current line top or bottom of page, like zz centers it!
- df<kbd>space</kbd> delete up to and including next space
- dt. -- delete until .
- ye -- copy/yank text from here to end of word
- cc -- cut current line or S
- B & E use whitespace a delimeters
- g; (last place you made a change!) and g, move forward and backwards through the changelist!
	- '. will go to last edited line and `. will go to last edit position 
	- ctrl-o (old) up jump list and ctrl-i down jump list through jump list :ju 
	- :changes - change list!
	- gv -- reselects last visual selection
	- :verbose set whatev? - tells you where it was set or unset
		- also works with maps and highlights 
- q: browse, edit and execute from your command history
- q/ for search history - ctrl-c to exit
- vim http://... to open web page source
- gi -- go to position of last insert stopped
- ctrl-z or for sub shell :sh to go out to zsh and the fg to come back
- == correct indentation based on line above
- mksession -- !
- `set list` to show whitespace etc
- = for fix indenting in GQL and JS etc!
- surround Vv and then S and what you want to surround with!!!
- G=gg -- auto re-indent entire document
- <kbd>`</kbd>> + <<kbd>.</kbd> -- jump to last mod location --  '. last line
- das or dis to delete sentence.
- dap or dip to delete a paragraph
- d) delete from cursor to end of sentence as long as there are no dots - use das usually
- dT<char> delete backwords to char
- gi - last insert location

Spelling:
- 1z= takes the first spelling suggestion
- zg - add spelling word
- z= -- look at spelling suggestions
</details>
