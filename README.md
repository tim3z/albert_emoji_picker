# Albert Emoji Picker
A simple offline emoji picker for albert.

Install by copying `EmojiPicker.py` into `~/.local/share/albert/org.albert.extension.python/modules`. 
Needs a font which can display the emojis.

This is just the result of an afternoon of hacking - a ton of improvements are possible...
* Not hardcoding the emojis
* An index datastructure to speed up the matching - though surprisingly speed seems to be okish even with this simplistic implementation
* Icons
* Better ranking of search results
* ...
