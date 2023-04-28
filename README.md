## dvorak-esdf-vim-corne-zmk-config

A firmware for the [custom Swept Corne split wireless mechanical keyboard](https://www.etsy.com/listing/1235225784/custom-swept-corne-split-wireless?click_key=74d726018ca7d05092a40855087bf090299eafaa%3A1235225784&click_sum=c7a5e75c&ref=shop_home_active_3) to support the needs of a Vim programmer that types in Dvorak and uses esdf for movement.

```
layer 0
-------------------------------------------------------------------------------------
| TAB  |  '  |  ,  |  .  |  p   |  y  |          |  f  | g  | c  |  r  |  l  | /    |
| BKSP |  a  |  o  |  e  |  u   |  i  |          |  d  | h  | t  |  n  |  s  | ENT  |
| SHFT |  ;  |  q  |  j  |  k   |  x  |          |  b  | m  | w  |  v  |  z  | SHFT |
                   | ALT | CTRL | ESC |          | SPC | L2 | L1 |
```
```
layer 1
----------------------------------------------------------------------------------------
| TAB  |  !   |  @  |  #   | $    | %   |          | ^   | &  | *  |  (  |  )  | -     |
| BKSP |  1   |  2  |  3   | 4    | 5   |          | 6   | 7  | 8  |  9  |  0  | ENT   |
| SHFT |  F1  |  F2 |  F3  | .    | F5  |          | F6  | F7 | F8 |  F9 | F10 | SHIFT |
                    | ALT  | CTRL | SPC |          | SPC |    |    |
```
```
layer 2
----------------------------------------------------------------------------------------------
| TAB   |   !     |  @  |  UP  |  $   |  %     |          | ^   |  /  |  \  |  [  | ]  | "|" |
| BKSP  | HOME    | LFT | DOWN | RGT  | END    |          | =   |  <  |  >  |  (  | )  | ENT |
| SHIFT | scrnlft |  ~  | #    | .    | scrnrt |          | +   |  -  |  _  |  {  | }  | &   |
                        | LGUI | CTRL | SPC    |          | SPC |     |     |
```
```
layer 3
----------------------------------------------------------------------------------------------
| CTRL + SHFT + ESC | F1 | F2  | F3  | F4  | PSE  |          | PLY | 7 | 8   | 9 | - | /     |
| CTRL + ALT + DEL  | F5 | F6  | F7  | F8  | PREV |          | NXT | 4 | 5   | 6 | + | ENT   |
| SHIFT             | F9 | F10 | F11 | F12 | VDWN |          | VUP | 1 | 2   | 3 | . | SHIFT |
                               |     |     | ESC  |          | SPC | 0 | to0 |
```

##### CTRL + ALT = WIN
##### ALT + SHIFT = CAPS
##### SHIFT + ESC = BACKTICK
##### SHIFT + BACKSPACE = DELETE
##### L1 + L2 = L3
##### Shift keys are sticky, meaning they don't need to be held and are released after the next key is typed.


See the [config file](https://github.com/geektechniquestudios/zmk-config/blob/master/config/corne.keymap) to customize the layout for your needs. If you fork this repo and make changes, you can see your firmware build in the `Actions` tab.
