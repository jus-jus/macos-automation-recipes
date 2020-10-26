# macOS Automation Recipes

Text selection is widely used and handy feature. It would be unimmaginable to use a text box without copying, cutting, pasting, selecting, undo or redo abilities.

Selecting a piece of text and passing it to the other program to process it would be very useful feature in UX that is usually missing for the general user.

That's where macOS Automation service comes in. It contains various tools that facilitate repetitive sequence automation by providing native tools to handle various integrations points.

Here is a list of useful automation scripts that could help to become more productive.

<!-- @import "[TOC]" {cmd="toc" depthFrom=2 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Selection](#selection)
  - [Make iPhone call from macbook](#make-iphone-call-from-macbook)
  - [Translate text with Google Translate](#translate-text-with-google-translate)
  - [Open TheSaurus](#open-thesaurus)
  - [Find selection in Google Maps](#find-selection-in-google-maps)
- [General services](#general-services)
  - [Open Google Translate popup](#open-google-translate-popup)
  - [Translate clipboard in Google Translate](#translate-clipboard-in-google-translate)
- [Tips](#tips)
- [Addendum](#addendum)

<!-- /code_chunk_output -->

## Selection

Scripts perform action with selected text

### Make iPhone call from macbook

When Apple introduced Continuity, have you noticed that only Safari browser has the ability to indicate a number to call? Wouldn't it be nice if that was possible everywhere? I mean everywhere.
This script allows to make a call to selected text. For safety, this script tries to validate the input and ignore any non numeric character.

`make-call-selection.workflow`

### Translate text with Google Translate

It helps a lot if you're not a native English speaker. Even if the one knows a lot of words, it is impossible to know all of them.

`google-translate-selection.workflow`

### Open TheSaurus

Writing text for non native English speaker is quite often encountered with shortage of words. To tackle this issue, let's open TheSaurus and see the alternative words.

`thesaurus-selection.workflow`

### Find selection in Google Maps

Significantly faster way to open address in google maps than opening Maps app or opening Google Maps in a separate tab

`address-google-maps.workflow`

opens google maps for selected text

## General services

Some programs do not expose interface to consume macOS services that take advantage of selected text. However, every program has support for general services that are available for all programs in macOS.

### Open Google Translate popup

Instead of translating selected text, just open the Google Translate pop-up and write the word or phrase to translate.

`open-google-translate.workflow`

### Translate clipboard in Google Translate

Want translate word but the program does not support macOS text election service? Not a problem! Copy selected to clipboard and translate text that's in the clipboard.

`google-translate-clipboard.workflow`



## Tips

Use **⌘+⇧+S** to switch translation direction. The shortcut binding comes from Google Translate itself. Very convenient if there's need to translate the other way around.



## Addendum

Using macOS Safari built-in pop-up instead of using any browser. Why? It works nicely. The benefits are that I can control the size of the window, the position on screen - now it open window based on mouse position which is convenient and most importantly the window opens in full-screen seamlessly.


