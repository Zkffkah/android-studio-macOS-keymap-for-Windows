# android-studio-macOS-keymap-for-Windows

================================

1. Use SharpKeys app to swap modifier keys.

    LControl => Winkey
    
    Winkey => LAlt
    
    LAlt => LControl
    
    ![SharpKeys Settings](https://raw.githubusercontent.com/lowwor/android-studio-macOS-keymap-for-Windows/master/sharpkey_settings.png)

   > This is not typical Mac Control-Alt-Command layout, but don't worry, we will make shortcuts work in the same manner your fingers are used to. The reason why we can't simply swap Win & Alt is because IntelliJ IDEA requires a lot of shortcuts with "Command" key (which would be Windows key in our case), and it's impossible to make them work well. So we stick to more traditional "Control"-shortcuts on the OS level. But, again, don't worry, in the end shortcuts physically will be the same os on Mac OS X.

2. Use AutoHotkey script "OS X keyboard for Windows" to remap basic shortcuts (see "OS X keyboard for Windows" AutoHotkey script).


3. For IntelliJ IDEA users:

    3.1. Disable Winkey OS shortcuts (e.g. http://www.askvg.com/tip-how-to-disable-all-win-keyboard-shortcuts-hotkeys-in-windows/)
    
    3.2. Use provided "Mac OS X 10_5_for_Windows" keymap.
    http://codingmatters.blogspot.co.uk/2010/02/i-always-thought-its-not-possible-to.html
    http://youtrack.jetbrains.com/issue/IDEA-119932








Thanks to https://gist.github.com/fljot/58e46c92e99e7072ab56
