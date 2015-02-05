# Hush
An XChat plugin to suppress join, part, and nick change message from inactive users.  Inspired by the WeeChat smart filter plugin.

# Usage
Place in ~/.config/xchat2 and XChat will auto-load the file.  Hush is "on" by default, but you can disable it with `/hush off` or see its status with
`/hush status`

# Limitations
Hush records activity across all channels.  So if you are in #foo and #bar
with jane and she has been talking a lot in #foo but silent in #bar, when jane
quits, you will still see her quit message in #bar.
