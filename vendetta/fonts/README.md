# Fonts

fonts are constructed using this, easy json:

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

so, explanations:
* spec - _no description_
* name - any, name of the font pack
* previewText - any(?), text to preview the pack with
(may be inacurrate / didnt tested yet)

How to change the fonts?
> The JSON I gave you above, has all (as of current date) fonts Discord use. So just append the links to your .ttf in the empty fields, and remove all others which dont have a font / which you dont want to replace
Explanation of the JSON was provided by Nexx Pid from Revenge-mod Discord server
