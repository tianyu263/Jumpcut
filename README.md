Fork from http://jumpcut.sourceforge.net [Jumpcut 0.63 of Steve Cook].

=About=
Jumpcut is an application that provides "clipboard buffering" — that is, access to text that you've cut or copied, even if you've subsequently cut or copied something else. The goal of Jumpcut's interface is to provide quick, natural, intuitive access to your clipboard's history.

=Using Jumpcut=
Jumpcut is designed to be simple. Download the application, double-click the .tgz file to open it, and drag the application (the one with the pretty scissors icon) to your Applications directory. Launch Jumpcut. A scissors icon will appear in your menu bar. Now whenever you cut or copy a text item, it'll be added to the "stack" of clippings that Jumpcut has recorded. Clippings can be accessed in one of two ways:

    *Under the menu bar
    Choose a clipping from the Jumpcut menu.

    *Through a pop-up bezel
    In any application into which you want to paste an item from Jumpcut's stack, press the hotkey to activate Jumpcut's bezel. (The default value for this hotkey is Control-Option-V.) A little window like the one you see when using the application switcher or the brightness controls will appear. While holding the modifier keys (for the default hotkey, this is the Control-Option combo), use the arrow keys to scroll through the stack.

When you've selected a clipping, Jumpcut will put it on the pasteboard and attempt to paste it into your application. It does this by mimicking a user typing Command-V, so unusual applications which don't use this to indicate "Paste" will be confused. The clip will still be on the pasteboard, though, so you can paste it normally. If Command-V is used in a non-standard way in applications you are trying to paste to, a preference is available to disable the "paste" action for clippings selected from the menu bar. In this case, choose the clipping and paste however your application asks you to do it.

I've tried to allow a few different methods for navigating in the bezel. You can move down the stack using the right arrow, down arrow, or "V" key; you can move up the stack using the left arrow, up arrow, or "Shift-V". Home moves to the beginning, and End moves to the end. Page Up and Page Down scroll through the stack more quickly. If you change your mind and decide not to paste the application, hit escape to make the bezel vanish. A "sticky bezel" preference is available; if it's selected, you must explicitly hit return or escape to dismiss the bezel.

Jumpcut remembers the last clipping you selected using the bezel. The next time you bring the bezel up, it will start with that clipping unless it's scrolled off the stack.
