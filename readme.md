[![MELPA](https://melpa.org/packages/smart-tabs-mode-badge.svg)](https://melpa.org/#/smart-tabs-mode)

My fork.
I will try to follow changes done by others and integrate it here.
I may not push it back to the original until I see some activity.

Smart Tabs
==========
*Indent with tabs; align with spaces*
<!-- ![“Tabs.” “Spaces.” “Both.”][tsb] -->

See [EmacsWiki › SmartTabs][est] for details about the idea this package enables.

Summary:

    // Tab size: 4                // Tab size: 2
    if(foo) {                     if(foo) {
    --->char quux[4] = {0, 1,     ->char quux[4] = {0, 1,     // "0" and "2"
    --->................2, 3};    ->................2, 3};    // remain aligned
    }                             }

Tabs are only used at the **beginning of lines**. Everything else, like ASCII art and tables, should be formatted with spaces.

Tabs are only used for **expressing the indentation level**. One tab per “block” – any remaining whitespace is spaces only.

[est]: http://www.emacswiki.org/emacs/SmartTabs
<!-- [tsb]: http://www.emacswiki.org/pics/static/TabsSpacesBoth.png -->
