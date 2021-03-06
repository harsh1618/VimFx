# VimFx - Vim keyboard shortcuts for Firefox

![VimFx Logo](https://raw.github.com/akhodakivskiy/VimFx/develop/icon-large.png)

**Extension AMO page**: https://addons.mozilla.org/en-US/firefox/addon/vimfx.

**Mailing list**: [vimfx@librelist.com](mailto:vimfx@librelist.com?subject=Subscribe) (just send an email to subscribe)

Contribute your localization! See `locale` folder.

Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening issues and pull requests.

## Overview

[VimFx](https://addons.mozilla.org/en-US/firefox/addon/vimfx/)
is a [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/fx/#desktop)
extension which introduces Vim-style keyboard shortcuts for browsing and navigation,
significantly reducing the use of mouse, and allowing your hands to rest on the home row.

VimFx was inspired by [Vimperator](http://www.vimperator.org/)
and designed after [Vimium](http://vimium.github.com/) for
[Google Chrome](https://www.google.com/intl/en/chrome/browser/) preserving the shortcuts and behavior.
If your are used to Vimium then it will be easy to get started with VimFx.

## Why VimFx was created

Even before Vimium there was Vimperator for Firefox.  In my opinion the problem
with Vimperator is that it has too many features and aggressively changes
the default Firefox appearance and behavior. Vimium was developed for Google Chrome
and it was exactly what I needed in terms of added functionality. That's why I decided
to develop similar extension for Firefox.

VimFx will be nice to your browser and to your habits. Promise.

## Key Features

- Concise shortcuts for most commonly performed actions
- Follow and access controls on the page using hint markers
- Easy access to the keyboard shortcuts dialog, which describes and lets you customize all available shortcuts (press ?)

## Shortcuts

This is a text representation of the keyboard shortcuts dialog within the extension. Might not be up to date.
Press ? or use the toolbar button to open the dialog, which helps you remember the shortcuts, and lets you customize them.

Global shortcut to enable/disable VimFx: `shift-alt-v`

### Dealing with URLs

    o       Focus the Address Bar
    O       Focus the Search Bar
    p       Navigate to the address in the clipboard
    P       Open new tab and navigate to the address in the clipboard
    yf      Copy link url to the clipboard
    vf      Focus element
    yy      Copy current page link to the clipboard
    r       Reload current page
    R       Reload current page and all the assets (js, css, etc.)
    ar      Reload pages in all tabs
    aR      Reload pages in all tabs including assets (js, css, img)
    s       Stop loading current page
    as      Stop loading pages in all tabs

### Navigating the Page

    gg      Scroll to the Top of the page
    G       Scroll to the Bottom of the page
    j,c-e   Scroll Down
    k,c-y   Scroll Up
    h       Scroll Left
    l       Scroll Right
    d       Scroll half a Page Down
    u       Scroll half a Page Up
    c-f     Scroll full Page Down
    c-b     Scroll full Page Up

### Working with Tabs

    t       Open New Blank tab
    J,gT    Go to the Previous tab
    K,gt    Go to the Next tab
    c-J     Move current tab to the Left
    c-K     Move current tab to the Right
    gh      Navigate to the Home Page
    gH,g^   Go to the First tab
    gL,g$   Go to the Last tab
    x       Close current tab
    X       Restore last closed tab

### Browsing

    f       Follow a link on the current page
    F       Follow a link on the current page in a new tab
    af      Follow multiple links on the current page
    [       Follow the Previous page link on the current page
    ]       Follow the Next page link on the current page
    gu      Go up one level in the URL hierarchy
    gU      Go up to root of the URL hierarchy
    H       Go Back in history
    L       Go Forward in history

### Misc

    /       Enter Find mode
    a/      Enter Find mode to highlight all matches
    n       Go to the next Find match
    N       Go to the previous Find match
    i       Enter insert mode: Ignore all commands
    ?       Show this dialog
    :       Open Developer Toolbar
    Esc     Enter normal mode (remove hint markers, exit insert mode) or blur/close active element

Can't see a link hint, because it's overlapped by another? Try pressing space or shift-space!
