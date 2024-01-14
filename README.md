## Ergoist layout
- Raise, lower and one conditional layer. 
- Caps words combo
- Home row mods for `Ctrl` and `Alt` (and `Shift` also, but I don't use it much)

### Default layer
It has letters and modifiers.
The layout doesn't contain any `Ctrl` or `Alt` keys, but they are accessible via [Hold-Tap ZMK feature](https://zmk.dev/docs/behaviors/hold-tap#hold-tap) on the home rowd. 
Basically it means that you can assign two different keys on one button and depending on how long you hold the button you will get different result. Works fine for me, the hold time is 300 ms, not too long before I can use `Alt` key in combinations. 
![0](/assets/l0.jpg)

### Lower
This layer is for navigation, numbers and functional keys
![1](/assets/l1.jpg)

### Raise
This layer is for symbols.
Numbers are on the raise layer so it's convenient to symbols on a dedicated layout, makes the access much easier.
![2](/assets/l2.jpg)

### Conditional layer
It gets activated when you press raise and lower buttons. 
I moved bluetooth config keys alongside to Fn modifiers for sound volume and brightness here. Just to make sure I adjust these things intentionally. 
![3](/assets/l3.jpg)

### Caps Words combo
It is activated with two Shift keys pressed together. 
The key feature of it is to allow you to define keys that will keep it turned on, and when you press any other key it automatically turns off. 
For instance for this keyboard it is configured that Caps Words allow you to press navigation buttons, backspace and enter buttons, while any other button will turn it off and you continue typing in a lower case. 
More info here: [Caps Words ZMK docs](https://zmk.dev/docs/behaviors/caps-word)
![combo1](/assets/combo1.jpg)