# 𝕬𝖉𝖊𝖑𝖍𝖊𝖎𝖉 - WIP

The Adelheid is a 75% Alice-like keyboard.  
It's a fork of FateNozomi's Arisu files: [Arisu PCB](https://github.com/FateNozomi/arisu-pcb) &amp; [Arisu case](https://github.com/FateNozomi/arisu-case)

![adelheid](https://gist.githubusercontent.com/floookay/7bf6511a8d84804d32de4d7bbe3bd0fb/raw/559336bcb5f8c04bbea9ad8aab7397812ab72859/adelheid.jpg)
<!-- ![adelheid side](https://gist.githubusercontent.com/floookay/7bf6511a8d84804d32de4d7bbe3bd0fb/raw/4545813142abf2e65902b7caca10f7a3b39ebaed/side_shadow.jpg) -->

This repository includes files for:

- the Adelheid PCB &rarr; [README.md](./pcb/README.md)
- a layered case &rarr; [README.md](./case/README.md)
- a wrist rest &rarr; [README.md](./wrist-rest/README.md)

## Changes in this fork

Here is a list of things I added in this fork in comparison to the Arisu:

- [x] added an angled spaced function row
- [x] added option for stepped caps lock
- [x] replaced micro usb port with tht mini usb port
- [x] added single color underglow and key lighting **(WIP - underglow works, but per key LEDs have not been tested yet)**

for a visual comparison see [here](./IMAGES.md#arisu-comparison)

## Layout

A spaced 75% layout on top of the Alice/Arisu-layout.

[Keyboard-Layout-Editor](http://www.keyboard-layout-editor.com/#/gists/4262535adb5ac81a913edbebc4de8226) [(raw)](https://gist.github.com/floookay/4262535adb5ac81a913edbebc4de8226)  
![adelheid layout](https://gist.githubusercontent.com/floookay/7bf6511a8d84804d32de4d7bbe3bd0fb/raw/4545813142abf2e65902b7caca10f7a3b39ebaed/layout.png)  
<!-- ![adelheid top view](https://gist.githubusercontent.com/floookay/7bf6511a8d84804d32de4d7bbe3bd0fb/raw/4545813142abf2e65902b7caca10f7a3b39ebaed/top_view.jpg) -->

## Firmware

<https://github.com/floookay/qmk_firmware/tree/adelheid/keyboards/adelheid>  
And hopefully soon in the main QMK repository. I'll have to test the lighting support first though, before I'll open a pull request.

## Images

For more images see this [image carousel](./IMAGES.md).

## Miscellaneous

> Why?

Good question, I think accessing the function keys with a layer on the number row is the superior method as it's faster and more comfortable because you don't have to move your hands that much. But I found myself trying to access the function row one-handedly quite often and nothing beats the comfort of pressing a single dedicated key. So that's why I added the function row. By default you can still access the function keys via the number row on the secondary layer.  

> Where does the name Adelheid come from?

I thought it'd be nice to continue the somewhat tradition of naming Alice-clones by putting a spin on the forename Alice, just like the Arisu, Lisa and Majbritt did. I chose Adelheid as a German spin on the name since that's where I'm from.  
The typeface is called Fraktur and was the dominant typeface during the time when Adelheid was one of the most popular names.

> Will you add more keys to the bottom row or a second B key?

I don't plan on changing the bottom row or adding a second B key. In my opinion the keyboard looks the best and most balanced the way Fate designed it.

## TODO's

- **test lighting support**
- add 3d printable case files
- maybe rework the switch positions/cutouts in all files slightly (function row margin is larger at the bottom of the key, F7 is slightly more inwards)
