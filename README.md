# no-console.js
# made by mereniskender
# in case of any problems, don't hesitate to contact me
# contact: discord -> iskender#8383
# contact: e-mail  -> iskender83@pm.me

# Mail Me
mailto:iskender83@pm.me?subject=Help%20About%20no-console.js

https://iskenderjs.github.io/mail

No-Console.js is used for blocking people from accessing:

- Developer Tools, [ F12 ]
- Javascript Console, [ CTRL + SHIFT + J ]
- Inspect Elements,  [ CTRL + SHIFT + I ]
- View Page Source, [ CTRL + U ]
- Save Page Source, [ CTRL+ S ]
- Context Menu; [ Right Click]

or logging the user ip and the event with discord webhook API.

It also has an option to disable javascript console output and autocorrect.

Since this is a new (and also my first) repository, there might be a lot of bugs as you've expected, I will try to fix them.
Thanks for using No-Console.js




--------------------------------------------------------------------------------------------------------------------------------------------

USAGE 

--------------------------------------------------------------------------------------------------------------------------------------------

If you want to log and block all of the suspected actions, don't change anything.

If you want ONLY to log all of the suspected actions;

- Comment the first block of code,
- Uncomment the second block of code.

If you want to log and block all of the suspected actions  EXCEPT RIGHT CLICK;
- Comment the first block of code,
- Uncomment the third block of code.

If you want to log all of the suspected actions  EXCEPT RIGHT CLICK;
- Comment the first block of code,
- Uncomment the fourth block of code.

If you don't want to send the copyright message,
- Uncomment the first line of code.

If you want to;
- Auto-clear all output,
- Disable document.designMode,
- Disable auto-complete,

Place the function "disableConsole" into page onload.
```<body onload="disableConsole()">```


DO NOT FORGET TO ADD YOUR WEBHOOK URL ( Line 6 )
