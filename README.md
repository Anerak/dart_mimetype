# Dart Mimetype

[**Dart**][1] appeared for the first time back in 2011 ([according to Wikipedia][2]).

Surprisingly, couldn't find any mime-type configuration for it, so I decided to create one myself.

## Requirements

* **xdg-mime**

## Simple install

    wget https://raw.githubusercontent.com/Anerak/dart_mimetype/master/x-dart.xml
    xdg-mime install x-dart.xml

## Icon

The ones I made are based on ["Paper Icons"][3] by [Sam Hewitt][4]

There are two options: solid or outline.

Choose the one that you like the most!

Place it at the folder of your icons theme.

    # Example
    /usr/share/icons/[icon theme]/scalable/mimetypes/text-x-dart.svg

[1]: https://dart.dev
[2]: https://en.wikipedia.org/wiki/Dart_(programming_language)#cite_note-12
[3]: https://snwh.org/paper
[4]: https://samuelhewitt.com/
