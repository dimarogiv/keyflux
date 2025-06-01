# keyflux
Ergonomic keyboard layout with easy access to modifier keys

## Introduction
Keyflux is mainly targeted at power users and others who value ergonomics, flow
of thought and speed.

## Features
- Based on programmer Dvorak
- Easy access to modifier keys
- Split arrangement for ergonomic spacing
- Multiple layers
- Digits and special symbols are separated from the main layer
- Special symbols are doubled to the first layer for easy access
- All of the hard-to-reach keys are removed

## Layer system
The main layout looks like the regular Dvorak layout with the upper row of
special symbols arranged like in programmers Dvorak and `Esc` right near the left
pinkie for easy access for Vim users. All modifier keys are accessed with
thumbs.
```
┌─────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬──────┐
│$  Fn│ &  │ [  │ {  │ }  │ (  │ =  │    │ }  │ *  │ )  │ +  │ ]  │ !  │ #  │    │ F1   │
┢━━━━━┱────┴┬───┴─┬──┴──┬─┴───┬┴────┼────┴┬───┴─┬──┴──┬─┴───┬┴────┼────┴┬───┴─┲━━┷━━━━━━┪
┃Tab ↹┃ ;   │ ,   │ .   │ P   │ Y   │     │ F   │ G   │ C   │ R   │ L   │ /   ┃Backspace┃
┃Lt   ┃ :   │ <   │ >   │     │     │     │     │     │     │     │     │ ?   ┃ ⌫       ┃
┣━━━━━┻━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃Esc    ┃ A   │ O   │ E   │ U   │ I   │ @   │ D   │ H   │ T   │ N   │ S   │ -   ┃ Enter ┃
┃       ┃     │     │     │  _  │     │     │     │  _  │     │     │     │ _   ┃ ⏎     ┃
┡━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┲━━━━┻━━━━━━━┫
│        ┃ '   │ Q   │ J   │ K   │ X   │     │ B   │ M   │ W   │ V   │ Z   ┃            │
│        ┃ "   │     │     │     │     ◜◝    │     │     │     │     │     ┃            │
├────────┺━━━┮━┵━━━┮━┵━━━┳━┵━━━┳━┵━━━┱─◟◞──┲━┵━━━┳━┵━━━┳━┵━━━┱━┵━━━┮━┵━━━┮━┹────────────┤
│            │     │     ┃Lvl3 ┃Space┃LAlt ┃RAlt ┃Space┃Lvl3 ┃     │     │              │
│            │     │     ┃     ┃ ␣   ┃     ┃     ┃ ␣   ┃     ┃     │     │              │
├─────┬──────┼─────╆━━━━━╋━━━━━┻━━━━━┻━━━━━┻━━━━━┻━━━━━╋━━━━━╉─────┼─────╆━━━━┳━━━┳━━━━━┪
│     │      │     ┃LCtrl┃ Shift                       ┃RCtrl┃     │     ┃PgUp┃Up ┃PgDn ┃
│     │      │     ┃     ┃  ⇧                          ┃     ┃     │     ┃Left┃Dn ┃Right┃
└─────┴──────┴─────┺━━━━━┻━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┻━━━━━┹─────┴─────┺━━━━┻━━━┻━━━━━┛
```
To access special symbols and digits hold one of the `Lvl3` keys. If you want to
use digits hold the right `Lvl3`, and use the left one otherwise.
```
┌─────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬──────┐
│$  Fn│ &  │ [  │ {  │ }  │ (  │ =  │    │ }  │ *  │ )  │ +  │ ]  │ !  │ #  │    │ F1   │
┢━━━━━┱────┴┬───┴─┬──┴──┬─┴───┬┴────┼────┴┬───┴─┬──┴──┬─┴───┬┴────┼────┴┬───┴─┲━━┷━━━━━━┪
┃Tab ↹┃ ;   │ 7   │ 8   │ 9   │ \   │     │ |   │ {   │ #   │ *   │ }   │ ~   ┃Backspace┃
┃Lt   ┃ :   │     │     │     │     │     │     │     │     │     │     │     ┃ ⌫       ┃
┣━━━━━┻━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃Esc    ┃ 0   │ 4   │ 5   │ 6   │ =   │ @   │ %   │ (   │ &   │ $   │ )   │ -   ┃ Enter ┃
┃       ┃     │     │     │  _  │     │     │     │  _  │     │     │     │ _   ┃ ⏎     ┃
┡━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┲━━━━┻━━━━━━━┫
│        ┃ '   │ 1   │ 2   │ 3   │ `   │     │ ^   │ [   │ +   │ !   │ ]   ┃            │
│        ┃ "   │     │     │     │     ◜◝    │     │     │     │     │     ┃            │
├────────┺━━━┮━┵━━━┮━┵━━━┳━┵━━━┳━┵━━━┱─◟◞──┲━┵━━━┳━┵━━━┳━┵━━━┱━┵━━━┮━┵━━━┮━┹────────────┤
│            │     │     ┃Lvl3░┃Space┃LAlt ┃RAlt ┃Space┃Lvl3░┃     │     │              │
│            │     │     ┃░░░░░┃ ␣   ┃     ┃     ┃ ␣   ┃░░░░░┃     │     │              │
├─────┬──────┼─────╆━━━━━╋━━━━━┻━━━━━┻━━━━━┻━━━━━┻━━━━━╋━━━━━╉─────┼─────╆━━━━┳━━━┳━━━━━┪
│     │      │     ┃LCtrl┃ Shift                       ┃RCtrl┃     │     ┃PgUp┃Up ┃PgDn ┃
│     │      │     ┃     ┃  ⇧                          ┃     ┃     │     ┃Left┃Dn ┃Right┃
└─────┴──────┴─────┺━━━━━┻━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┻━━━━━┹─────┴─────┺━━━━┻━━━┻━━━━━┛
```
To access `F1-12` keys press and hold the `$` key for more than 150 ms.
```
┌─────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬──────┐
│░░░Fn│ F1 │ F2 │ F3 │ F4 │ F5 │ F6 │ F7 │ F8 │ F9 │ F10│ F11│ F12│ Hm │ En │    │ F1   │
┢━━━━━┱────┴┬───┴─┬──┴──┬─┴───┬┴────┼────┴┬───┴─┬──┴──┬─┴───┬┴────┼────┴┬───┴─┲━━┷━━━━━━┪
┃Tab ↹┃ ;   │ ,   │ .   │ P   │ Y   │     │ F   │ G   │ C   │ R   │ L   │ /   ┃Backspace┃
┃Lt   ┃ :   │ <   │ >   │     │     │     │     │     │     │     │     │ ?   ┃ ⌫       ┃
┣━━━━━┻━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃Esc    ┃ A   │ O   │ E   │ U   │ I   │ @   │ D   │ H   │ T   │ N   │ S   │ -   ┃ Enter ┃
┃       ┃     │     │     │  _  │     │     │     │  _  │     │     │     │ _   ┃ ⏎     ┃
┡━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┲━━━━┻━━━━━━━┫
│        ┃ '   │ Q   │ J   │ K   │ X   │     │ B   │ M   │ W   │ V   │ Z   ┃            │
│        ┃ "   │     │     │     │     ◜◝    │     │     │     │     │     ┃            │
├────────┺━━━┮━┵━━━┮━┵━━━┳━┵━━━┳━┵━━━┱─◟◞──┲━┵━━━┳━┵━━━┳━┵━━━┱━┵━━━┮━┵━━━┮━┹────────────┤
│            │     │     ┃Lvl3 ┃Space┃LAlt ┃RAlt ┃Space┃Lvl3 ┃     │     │              │
│            │     │     ┃     ┃ ␣   ┃     ┃     ┃ ␣   ┃     ┃     │     │              │
├─────┬──────┼─────╆━━━━━╋━━━━━┻━━━━━┻━━━━━┻━━━━━┻━━━━━╋━━━━━╉─────┼─────╆━━━━┳━━━┳━━━━━┪
│     │      │     ┃LCtrl┃ Shift                       ┃RCtrl┃     │     ┃PgUp┃Up ┃PgDn ┃
│     │      │     ┃     ┃  ⇧                          ┃     ┃     │     ┃Left┃Dn ┃Right┃
└─────┴──────┴─────┺━━━━━┻━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┻━━━━━┹─────┴─────┺━━━━┻━━━┻━━━━━┛
```
To switch to an alternative language layout there is `Lt` key. Holt it for more
than 150 ms and choose your layout.
```
┌─────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬──────┐
│$  Fn│ &  │ [  │ {  │ }  │ (  │ =  │    │ }  │ *  │ )  │ +  │ ]  │ !  │ #  │    │ F1   │
┢━━━━━┱────┴┬───┴─┬──┴──┬─┴───┬┴────┼────┴┬───┴─┬──┴──┬─┴───┬┴────┼────┴┬───┴─┲━━┷━━━━━━┪
┃░░░░░┃ Alt │ Orig│     │     │     │     │     │     │     │     │     │     ┃Backspace┃
┃Lt░░░┃     │     │     │     │     │     │     │     │     │     │     │     ┃ ⌫       ┃
┣━━━━━┻━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃Esc    ┃     │     │     │     │     │     │     │     │     │     │     │     ┃ Enter ┃
┃       ┃     │     │     │  _  │     │     │     │  _  │     │     │     │     ┃ ⏎     ┃
┡━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┲━━━━┻━━━━━━━┫
│        ┃     │     │     │     │     │     │     │     │     │     │     ┃            │
│        ┃     │     │     │     │     ◜◝    │     │     │     │     │     ┃            │
├────────┺━━━┮━┵━━━┮━┵━━━┳━┵━━━┳━┵━━━┱─◟◞──┲━┵━━━┳━┵━━━┳━┵━━━┱━┵━━━┮━┵━━━┮━┹────────────┤
│            │     │     ┃Lvl3 ┃Space┃LAlt ┃RAlt ┃Space┃Lvl3 ┃     │     │              │
│            │     │     ┃     ┃ ␣   ┃     ┃     ┃ ␣   ┃     ┃     │     │              │
├─────┬──────┼─────╆━━━━━╋━━━━━┻━━━━━┻━━━━━┻━━━━━┻━━━━━╋━━━━━╉─────┼─────╆━━━━┳━━━┳━━━━━┪
│     │      │     ┃LCtrl┃ Shift                       ┃RCtrl┃     │     ┃PgUp┃Up ┃PgDn ┃
│     │      │     ┃     ┃  ⇧                          ┃     ┃     │     ┃Left┃Dn ┃Right┃
└─────┴──────┴─────┺━━━━━┻━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┻━━━━━┹─────┴─────┺━━━━┻━━━┻━━━━━┛
```
Since I used Ukrainian layout, which has too many letters, I needed to hide some
punctuation signs under some of the commonly used keys.
To access `.` hold `Lvl3` key, and to access `?` hold `Lvl3-Shift`.
```
┌─────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬──────┐
│$  Fn│ &  │ [  │ {  │ }  │ (  │ =  │    │ }  │ *  │ )  │ +  │ ]  │ !  │ #  │    │ F1   │
┢━━━━━┱────┴┬───┴─┬──┴──┬─┴───┬┴────┼────┴┬───┴─┬──┴──┬─┴───┬┴────┼────┴┬───┴─┲━━┷━━━━━━┪
┃Tab ↹┃ Й   │ Ц   │ У   │ К   │ Е   │     │ Н   │ Г   │ Ш   │ Щ   │ З   │ Х   ┃Backspace┃
┃Lt   ┃     │     │     │     │     │     │     │     │     │     │     │     ┃L3-> / ? ┃
┣━━━━━┻━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃Esc    ┃ Ф   │ І   │ В   │ А   │ П   │ Ї   │ Р   │ О   │ Л   │ Д   │ Ж   │ Є   ┃ Enter ┃
┃       ┃     │     │     │  _  │     │     │     │  _  │     │     │     │     ┃L3-> . ┃
┡━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┲━━━━┻━━━━━━━┫
│        ┃ Я   │ Ч   │ С   │ М   │ И   │     │ Т   │ Ь   │ Б   │ Ю   │ ,   ┃            │
│        ┃     │     │     │     │     ◜◝    │     │     │     │     │     ┃            │
├────────┺━━━┮━┵━━━┮━┵━━━┳━┵━━━┳━┵━━━┱─◟◞──┲━┵━━━┳━┵━━━┳━┵━━━┱━┵━━━┮━┵━━━┮━┹────────────┤
│            │     │     ┃Lvl3 ┃Space┃LAlt ┃RAlt ┃Space┃Lvl3 ┃     │     │              │
│            │     │     ┃     ┃ ␣   ┃     ┃     ┃ ␣   ┃     ┃     │     │              │
├─────┬──────┼─────╆━━━━━╋━━━━━┻━━━━━┻━━━━━┻━━━━━┻━━━━━╋━━━━━╉─────┼─────╆━━━━┳━━━┳━━━━━┪
│     │      │     ┃LCtrl┃ Shift                       ┃RCtrl┃     │     ┃PgUp┃Up ┃PgDn ┃
│     │      │     ┃     ┃  ⇧                          ┃     ┃     │     ┃Left┃Dn ┃Right┃
└─────┴──────┴─────┺━━━━━┻━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┻━━━━━┹─────┴─────┺━━━━┻━━━┻━━━━━┛
```
## Installation
Keyflux works on `kanata`. Install it with your package manager first, then do
```
sudo cp keyflux.kbd /etc/kanata.kbd
```
and restart the Kanata service with
```
sudo systemctl restart kanata
```
.
For Ukrainian or any other alternative layout to work you'll need to setup
configure Xkb appropriately. Open `/etc/X11/xorg.conf.d/00-keyboard.conf` with
the text editor of your choice and put something like this there:
```
Section "InputClass"
        Identifier "system-keyboard"
        MatchIsKeyboard "on"
        Option "XkbLayout" "us,ua"
        Option "XkbVariant" ",winkeys"
        Option "XkbOptions" "grp:caps_switch"
EndSection
```
In case you use Wayland this won't work.

## Note
Everything Kanata does is hooking into events from the kernel and interpreting
it the way you described in the configuration file. Therefore, it's crucial to
set the default QWERTY keyboard layout in your system settings.

## Contribution
Keyflux currently works only on GNU/Linux with Xorg. If you want to help the
project, I'd appreciate any help in adapting it for Wayland or Windows (e.g., with
AutoHotkey).
