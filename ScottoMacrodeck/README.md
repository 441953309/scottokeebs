# ScottoMacrodeck

An 11 key VIA compatible macro pad.
![ScottoMacrodeck](https://user-images.githubusercontent.com/8194147/213901543-e875c192-bdfa-46bb-9397-392630f1b53a.jpg)
![Matrix](https://user-images.githubusercontent.com/8194147/213901557-9f445609-5124-4fd6-97f3-8c42496b0aad.jpg)

# Parts

-   1x - [Arduino Pro Micro (Atmega32U4)](https://amzn.to/3LwgAUq)
-   1x - [GX16-10 Aviator Connector](https://amzn.to/3kzPGll)
-   5x - [M2x4mm Screw](https://amzn.to/3XRb5F3)
-   5x - [M2 Heat Set Insert](https://amzn.to/3Cr1m05)
-   11x - MX Switches
-   11x - 1u Keycaps

# Pins

This board is direct wired meaning each key goes directly to a pin with a shared ground. Pins refer to the number on the Pro Micro, for more info see [info.json](QMK/info.json).

-   **Pins** - 1, 0, 2, 3, 4, 5, 6, 7, 8, 9, A3

# Case

The controller is simply hot glued into the bottom of the case.

-   [Plate](Case/ScottoMacrodeck%20-%20Plate.stl)
-   [Case](Case/ScottoMacrodeck%20-%20Case.stl)

# Flashing

1. [Install QMK locally](https://github.com/qmk/qmk_firmware)
2. Make changes to the keymap if required.
3. Run `qmk flash -kb handwired/jscotto/ScottoMacrodeck -km via -c`.

## VIA

In order to make VIA work with this board you must download [via.json](via.json). Next go into VIA and under the settings tab, enable "Show Design tab". Finally, go to the Design tab and upload using the "Load" button next to "Load Draft Definition".

# License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/joe-scotto/scottokeebs/tree/main/ScottoMacrodeck">ScottoMacrodeck</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/joe-scotto">Joe Scotto</a> is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0