# zx-usb

Joystick buttons / Keyboard keys for Navigation:

Keys/Buttons used for navigation in menu and redefine screens:
- USB joystick=> Directions: any of the Joysticks's sticks. Fire: any of the 4 main buttons 1,2,3,4. Cancel: Select or Home. *Clear: Start or Extra button.
- USB keyboard=> Directions: Cursors, Keypad cursors. Fire: Enter in keyboard or Numeric pad. Cancel: ESC, Home, End, Keypad Home, Keypad End. *Clear: BACKSPACE, DEL.FORWARD, NUM(Supr)
- ZX Spectrum keyboard => Directions: Cursors (keys 5 Left, 6 Down, 7 Up, 8 Right), O (Left), P(Right), Q(Up), A(Down). Fire: 0, ENTER. Cancel: CAPS+SPACE. *Clear: SHIFT+Zero key (Delete)
* Clear is used only when moving into ZX Mini spectrum to select keys.

--------------

Main Menu:
	Move Direction to the Left/Right to navigate Main Menu. Fire to launch option.
	Icon Redefine Joy to enter redefinition of USB Joystick Buttons.
	Icon Redefine Key to enter redefinition of USB Keyboard Keys.
	Icon Load Defaults will revert all the Joy Buttons and Keyboard Keys to it's default. *
	Icon Discard Changes will discard the changes donde in redefine Joy and redefine Key. *
	Icon Save changes permanently will save the changes and mantained even you power-off the system. **
	Icon Exit to exit and restart ZX Spectrum. *
	
	*The changes are mantained only while the system is powered on. Powering-off the system will revert to the previous state. See note **.
	**Is required to use the Save changes permanently to retain the changes after a power-off.
	
--------------

Redefine Joysticks:
Each Joystick connected to one of the two usb ports have its own keys (repeat keys in both joysticks is permitted).

To select the joystick button to be configured you can use one of these methods:
1.-If you are using an USB joystick simply press the button you want to redefine (hold the key less than 2 secs).
2.-If you are using an USB joystick and need to redefine an specific button (ie a button the current joystick you are using does not have), press and hold any of the USB joystick buttons for 2 seconds. Use any of the Directions, Fire or Clear buttons. *Cancel button is not allowed for this method as it will exit redefining joystick going back to main menu.
3.-If you have only one Joystick connected in an USB port and need to redefine the other joystick, hold J in USB keyboard of ZX Spectrum keyboard while pressing the Joystick button you want to redefine (less than 2 seconds).
4.-If you are using an USB keyboard, press any of its Directions, Fire or Clear buttons. *Cancel button is not allowed for this method.
5.-Using ZX spectrum keyboard, press any of its Directions, Fire or Clear buttons. *Cancel keys are not allowed for this method.

Navigating Mode.
With method 3, 4 and 5, the top-left Button will flash in yellow colour and allow to navigate through the Joystick buttons to select the button you want to be edited.
Use Directions to navigate through Joystick buttons and select which of them to redefine:
Hold 2 seconds Cancel Joystick buttons to exit this mode. If you are using USB Keyboard or ZX Keyboard, pressing Cancel button exit inmediately this mode (no require holding 2 seconds).
Press Fire buttons to enter Assignment mode.

Assignment mode.
With method 1 and 2, the Button to be redefined will be marked in yellow solid and a flashing cursor appear in the ZX mini keyboard to navigate for assign keys.
Use Directions to navigate through ZX mini and select ZX Spectrum key to assign to the Button.
Press Fire to assign the key. You can assign two keys. If you want to assign only 1 key, select the same key two times.
Press Clear button to Clear assignment of the key.
Press Cancel button to cancel (and discard) the assignment.
In assignment mode, ZX mini keyboard will automatically select the previous assigned keys by default as begging key for the redefinition. If the key was not previously assigned, the default key is "1" for the 1st key to assign, and the 1st new-assigned key for the 2nd key.

Warning:
Changes in assignment of Buttons are applied (changed) inmediately but are not saved permanently, they are mantained while the ZX Spectrum is powered-on. Powering-off the ZX Spectrum will loose the changes.
To retain the changes permanently (even power-off) you have to return to Main Menu and select the option SAVE CHANGES PERMANENT.
-------------------------
Redefine Keyboard:

User can redefine only one set of assignments of USB Keyboard keys. There is only one set having one keyboard/keypad or even two keyboards/keypad (one of each attached to each usb port).

Edition is quite similar to Redefine Joy except you are required to hold 2 sec if using the USB keyboard to enter navigating mode, using Cancel or using Clear keys. Using USB Joystick buttons or ZX Spectrum keys does not required holding 2 sec as these are apply inmediately.

========================================
Addendum. Special Joysticks.

PS4 Dualshock. Upper pad can be used as mouse. L1 and R1 are Left and right click, L2 is middle click (and also can be defined as keys -both working as mouse buttons and keys at the same time -)
Steam Controller. Can be used with usb cable. If using Dongle, 1st usage must be paired in a PC.
