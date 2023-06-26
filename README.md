# ThinkPad Dock Mount
The ThinkPad Dock Mount is a 3D printable wall mount for Lenovo "brick-style" ThinkPad docks. Key features are:
* Fits all the black "brick-style" ThinkPad docks (including the popular USB-C Dock Gen 2 and Thunderbolt 3 Dock Gen 2)
* Easy slide-in / slide-out with cables attached
* Mountable on a wall or under a table
* Power button and all inputs outputs stay fully accessible
* Reduced print time & lowered filament use (scroll down for customizeable version on GitHub)

Please also checkout my related [Thingiverse project](https://www.thingiverse.com/thing:6096753) if you prefer downloading and printing from there.

## Which file for which dock?
There are four different STL files that fit all nine common "brick-style" Lenovo ThinkPad docks.

The file "ThinkPad_Dock_Mount_USBC.stl" fits
* Think Pad USB-C Dock ([40A9](https://support.lenovo.com/us/en/accessories/acc100348-thinkpad-usb-c-dock-overview-and-service-parts
))

The file "ThinkPad_Dock_Mount_USBC2.stl" fits
* ThinkPad USB-C Dock Gen 2 ([40AS](https://support.lenovo.com/us/en/accessories/acc500106-thinkpad-usb-c-dock-gen-2-overview-and-service-parts
))
* ThinkPad Universal USB -C Smart Dock ([40B2](https://support.lenovo.com/us/en/accessories/acc500253-thinkpad-universal-usb-c-smart-dock-overview-and-service-parts
))
* ThinkPad Universal USB-C Dock ([40AY](https://support.lenovo.com/us/en/solutions/pd500519-thinkpad-universal-usb-c-dock-overview-and-service-parts
))

The file "ThinkPad_Dock_Mount_TB3_TB4.stl" fits
* ThinkPad Thunderbolt 3 Dock ([40AC](https://support.lenovo.com/us/en/solutions/acc100356-thinkpad-thunderbolt-3-dock-overview-and-service-parts
))
* ThinkPad Thunderbolt 3 Dock Gen 2 ([40AN](https://support.lenovo.com/us/en/solutions/pd500265-thinkpad-thunderbolt-3-dock-gen-2-overview-and-sevice-parts
))
* ThinkPad Universal Thunderbolt 4 Dock ([40B0](https://support.lenovo.com/us/en/solutions/pd500503-thinkpad-universal-thunderbolt-4-dock-overview-and-service-parts
))
* ThinkPad Universal Thunderbolt 4 Smart Dock ([40B1](https://support.lenovo.com/us/en/accessories/acc500254-thinkpad-universal-thunderbolt-4-smart-dock-overview-and-service-parts
))

The file "ThinkPad_Dock_Mount_HYB.stl" fits
* ThinkPad Hybrid USB-C with USB-A Dock ([40AF](https://support.lenovo.com/us/en/solutions/pd500180-thinkpad-hybrid-usb-c-with-usb-a-dock-overview-and-service-parts
))

In case you are unsure which dock you have, you can also check the following table for measurements

| Name | Code | L (mm) | W (mm) | H (mm) |
| -- | -- | -- | -- | -- |
| [ThinkPad USB-C Dock](https://support.lenovo.com/us/en/accessories/acc100348-thinkpad-usb-c-dock-overview-and-service-parts) | 40A9 | 171 | 80 | 33 |
| [ThinkPad USB-C Dock Gen 2](https://support.lenovo.com/us/en/accessories/acc500106-thinkpad-usb-c-dock-gen-2-overview-and-service-parts) | 40AS | 171 | 80 | 31 |
| [ThinkPad Universal USB -C Smart Dock](https://support.lenovo.com/us/en/accessories/acc500253-thinkpad-universal-usb-c-smart-dock-overview-and-service-parts) | 40B2 | 171 | 80 | 31 |
| [ThinkPad Universal USB-C Dock](https://support.lenovo.com/us/en/solutions/pd500519-thinkpad-universal-usb-c-dock-overview-and-service-parts) | 40AY | 171 | 80 | 31 |
| [ThinkPad Thunderbolt 3 Dock](https://support.lenovo.com/us/en/solutions/acc100356-thinkpad-thunderbolt-3-dock-overview-and-service-parts) | 40AC | 220 | 80 | 30 |
| [ThinkPad Thunderbolt 3 Dock Gen 2](https://support.lenovo.com/us/en/solutions/pd500503-thinkpad-universal-thunderbolt-4-dock-overview-and-service-parts) | 40AN | 220 | 80 | 30 |
| [ThinkPad Universal Thunderbolt 4 Dock](https://support.lenovo.com/us/en/solutions/pd500503-thinkpad-universal-thunderbolt-4-dock-overview-and-service-parts) | 40B0 | 220 | 80 | 30 |
| [ThinkPad Universal Thunderbolt 4 Smart Dock](https://support.lenovo.com/us/en/accessories/acc500254-thinkpad-universal-thunderbolt-4-smart-dock-overview-and-service-parts) | 40B1 | 220 | 80 | 30 |
| [ThinkPad Hybrid USB-C with USB-A Dock](https://support.lenovo.com/us/en/solutions/pd500180-thinkpad-hybrid-usb-c-with-usb-a-dock-overview-and-service-parts) | 40AF | 210 | 80 | 30 |

## Source files and alternative designs

The provided STL files should be good for most people. If have tried and tested them with the docks that I own; the prints came out well on my Bambu Lab P1P as well as on my Ender 3 V2 Neo using the following basic settings:
* 0.4mm nozzle
* 0.2mm layer height
* supports (for the "lip" that clicks the Dock into place!).

In case you would like to make changes, e.g. to
* placement of the wholes and selection of screws,
* cutouts, and
* tolerances,
I have inlcuded the Fusion360 source files. The model is parametrized so you can enter the dimensions of your dock and then export to STL for printing.