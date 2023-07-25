# no-console.js



# functionality


No-Console.js is used for blocking people from accessing:


- Developer Tools, [ F12 ]
- Javascript Console, [ CTRL + SHIFT + J ]
- Inspect Elements,  [ CTRL + SHIFT + I ]
- View Page Source, [ CTRL + U ]
- Save Page Source, [ CTRL+ S ]
- Context Menu; [ Right Click]
- Firefox Inspect Element [ CTRL + SHIFT + C ]
- Firefox Javascript Console [ CTRL + SHIFT + K ]

as well as logging the user ip and the event description with discord webhook API.

no-console.js has an option to auto disable:
- Autocorrect functionality in Javascript Console.
- Document Design Mode
- Javascript Console Output.

# Usage

The constant `WebhookURL` is your discord webhook api url.

Don't forget to add your webhook url, or change the constant `log` to false. This disables webhook api log feature.

If you don't want to block the actions, only log them, change the constant `block` to false. This disables the blocking feauture.

If you want to let your clients use context menu, change the constant `rightclick` to false. This enables context menu back.

If you don't want to disable autocorrect and design mode, change the constant `disable` to false. 

The constant `delay` indicates the delay between clearing the console.

