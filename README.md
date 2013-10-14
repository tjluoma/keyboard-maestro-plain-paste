keyboard-maestro-plain-paste
============================

Keyboard Maestro can be intimidating at first. I have made some extremely elaborate Keyboard Maestro macros, but today I want to show you the one that I absolutely, positively use most often.

Ready?

⌥ + V

*Mind-blowing, isn’t it?* OK, I can see you are not convinced yet. But wait until you hear what it does:

1.	Remove any formatting from the clipboard.[^Nomenclature] 

2.	Inserts the clipboard text *by typing*.

Here are a few of the scenarios when this comes in handy:

* any time you want to ‘paste’ text but do not wanted any formatting kept

* any time you are faced with a text field that does not respond to a ⌘ + V (paste) command

* any time you need to enter a phone number into one of those stupid web-forms that uses three different fields for a phone number (area code + prefix + suffix) where you can’t use ‘paste’ because it will put all of the digits into the first box

That might not sound like much, but I use this keyboard shortcut several times per day. I use it when I know that I don’t want formatting and am not sure if pasting it here will preserve formatting or not. I use it when I have to enter text into a field which limits the number of characters available, so I can tell when I hit the limit (which also often fails if you just `paste`). I use it when I want to make sure that I paste a URL and not an HTML link (as some apps -- I’m looking at you Messages.app on the Mac) want to make it.

Keyboard Maestro will type the characters as fast as possible, which is almost always plenty fast enough for me. If you have the full text of your novel on the clipboard, then maybe you want to use ⌘ + V to paste, but otherwise, I almost always find myself using ⌥ + V instead.

You can [download my Keyboard Maestro macro here](https://raw.github.com/tjluoma/keyboard-maestro-plain-paste/master/Type-Pasteboard.kmmacros), courtesy of Github. I have a bunch of other Keyboard Maestro macros available [on my Github account](https://github.com/tjluoma) as well.


[^Nomenclature]: or pasteboard, whichever name you prefer. Keyboard Maestro calls it the 'clipboard' so that's what I tend to use when talking about Keyboard Maestro.



