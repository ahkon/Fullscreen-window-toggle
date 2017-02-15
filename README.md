# Fullscreen-window-toggle (FWT)
An [AutoHotkey](https://autohotkey.com/) function that makes a window fullscreen. 

## Example Usage
The following shows two hotkey definitions that each call the FWT function. The first hotkey passes the active window. If a window handle is not passed to the function, as is the case for the second hotkey, it uses the window under the mouse.
```autohotkey
#w::FWT(WinExist("A"))    ; Win+W to fullscreen the active window
!^w::FWT()                ; Ctrl+Alt+W to fullscreen the window under the mouse
```
