# pastefile

A plugin for the [Profanity XMPP client](https://profanity-im.github.io/) that allows you to paste images and text from your clipboard and upload them as files.

If your clipboard holds an image, it will be uploaded in PNG format. Otherwise, if it holds text, the file type will automatically be detected from the text content (with .txt as fallback).

To build, run `make` and within profanity, run `/plugins install /path/to/pastefile.so`.

Command usage: `/pastefile`
