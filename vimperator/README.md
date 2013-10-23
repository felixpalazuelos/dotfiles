Vimperator config
=================

I love use my mechanical keyboard, and i hate to waste time, so Vimperator is pretty much the only choice i have for browsing the Internet.

## Learning Vimperator

### Tutorials

* [Vimperator Labs](http://www.vimperator.org/vimperator)
* [How to control Firefox using Vim keybindings](http://www.linux.com/feature/114419)
* [Hack and / - Dr hjkl Meets the Vimperator](http://www.linuxjournal.com/article/10636)

### Cheat Sheet
* [Visual map of the most basic commands](http://simplicityroad.livejournal.com/1938.html)
* [Interactive clickable cheat sheet which teaches many commands](http://vi.shiar.net/vimperator)
* [Another cheat sheet](http://www.cheat-sheets.org/#FirefoxAddOns)

### Quick Reference
*   `o` Open new link in current tab
*   `t` Open new link in new tab, also you can input keywords for search
*   `Tab`  select the candinates recycly
*   `f` Follow hint and open link in current tab, also very useful for locating user input forms
*   `F` Follow hint and open link in new tab
*   `gi` Locate the input form quickly
*   `Ctrl + A`  Move cursor to the beginning of the line in insert mode
*   `Ctrl + E`  Move cursor to the end of the line in insert mode
*   `Ctrl + U`  Delete the characters before cursor in insert mode
*   `Ctrl + K`  Delete the characters after cursor in insert mode
*   `gt` Jump to right tab
*   `gT` Jump to left tab
*   `g0` Jump to first tab
*   `g$` Jump to last tab
*   `H`  Navigate back
*   `L`  Navigate forward
*   `d`  Close current tab
*   `u`  Undo and reopen the lastest closed tab
*   `/`  Search in current page
*   `?`  Search in current page reversely
*   `:`  Command mode
*   `;c` Follow hint and open the right click menu(also called the contextual menu) for links

Installation
--------------------------------

Link the quickmarks:

    ln -s ~/dotfiles/vimperator/quickmarks ~/.vimperator/info/default/
