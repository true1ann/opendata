# Fonts

fonts packs are made using this structure:
```json
{
  "spec": 1,
  "name": "Font_name",
  "previewText": "Text_preview",
  "main": {
    "ABCGintoNord-ExtraBold": "",
    "ggsans-Bold": "",
    "ggsans-BoldItalic": "",
    "ggsans-ExtraBold": "",
    "ggsans-ExtraBoldItalic": "",
    "ggsans-Medium": "",
    "ggsans-MediumItalic": "",
    "ggsans-Normal": "",
    "ggsans-NormalItalic": "",
    "ggsans-Semibold": "",
    "ggsans-SemiboldItalic": "",
    "NotoSans-Bold": "",
    "NotoSans-ExtraBold": "",
    "NotoSans-Medium": "",
    "NotoSans-Normal": "",
    "NotoSans-NormalItalic": "",
    "NotoSans-Semibold": "",
    "SourceCodePro-Semibold": ""
  }
```

## JSON root
* `spec` - _no description_
* `name` - any, name of the font pack
* `previewText` - any(?), text to preview the pack with
(may be inacurrate / didnt tested yet)

## JSON fonts
* `ABCGintoNord-ExtraBold` - Header (eg Uh oh. / Crash header)
* `ggsans-*` - Default Discord font
* `NotoSans-*` - Default ***Internationl*** font (e.g. Russian)
* `SourceCodePro-Semibold` - Monospace fomt (eg codeblocks)

# Information
The JSON above has all (as of date when this file was changed) fonts Discord use. So just add the links to your .ttf files in the empty fields, and remove all others which you dont want to replace
> Explanation of the JSON was provided by Nexx from Revenge-mod Discord server, reworked by me

All paths to fonts ***MUST*** be an URL, ***you cannot use a local path, SFTP server path and such. only http:// OR https:// resources are supported.***
> Explanation of path links, added due to misunderstanding in the Revenge-mod Discord server
