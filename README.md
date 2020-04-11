# unicode-emojis-cpp
Provides unicode's own emoji data in a C++ interface

The data stored for each emoji is the unicode string corresponding to that emoji, a bitfield representing the platforms that support the emoji, the emoji's category, and the emoji's short name.

Some new emojis are not yet supported by any platforms. The platform support bitfields should be kept relatively up to date.

Skin tones are not yet supported by the library, but should not be too hard to implement.

Data acquired from Unicode's full v13.0 emoji list.
https://unicode.org/emoji/charts/full-emoji-list.html

Inspired by 99X Technology's emojicpp.
https://github.com/99xt/emojicpp
