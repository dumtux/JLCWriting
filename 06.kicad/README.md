# (DRAFT) [JLCPCB][1] SMT Assembly service - Raspberry Pico RP2040 KiCAD Design

In this article, we will explore how to get a KiCAD design fabricated and assembled by [JLCPCB][1] SMT Assembly service.
We'll use [RPi Pico Debugger Shoe][2]as a starting template.


## Prerequisites

* [KiCAD 6][3]
* [KiCAD JLCPCB tools][4]

If you're reading this article, you'll probably have KiCAD installed on your computer.
But if not, download and install [KiCAD 6][3] from the official website.

> The following contents of this article is tested with KiCAD version 6. Older versions or Nighty builds are not tested.

There are several plugins to export JLCPCB compitible fabrication files (Geber, BOM, CPL).
As we can see in the table, [KiCAD JLCPCB tools][4] has the best reputation and community support (at this time of writing).

GIthub Repository | Author | Star | Fork | Contributors | Last Updated
------------------|--------|------|------|--------------|-------------
[KiCAD JLCPCB tools](https://github.com/Bouni/kicad-jlcpcb-tools) | Bouni bouni@owee.de | 244 | 28 | 10 | Feb 2022
[KiCad JLCPCB BOM Plugin](https://github.com/wokwi/kicad-jlcpcb-bom-plugin) | Wokwi <https://wokwi.com/> | 110 | 25 | 3 | 2021
[KiJLC](https://github.com/fullyautomated/KiJLC) | Fully Automated <https://fully.automated.ee/> | 12 | 8 | 2 | 2021
[KiCad BOM CPL Plugin](https://github.com/prrvchr/KiCad-BOM-CPL-Plugin) | prrvchr prrvchr@gmail.com | 3 | 2 | 1 | 2020

Installing [KiCAD JLCPCB tools][4] on KiCAD is easy.

---

[1]: https://jlcpcb.com/HOT "JLCPCB Official Website"
[2]: https://github.com/ShawnHymel/rpi-pico-debugger-shoe "RPi Pico Debugger Shoe by Shawn Hymel"
[3]: https://www.kicad.org/download/ "KiCAD Official Download Page"
[4]: https://github.com/Bouni/kicad-jlcpcb-tools "KiCAD JLCPCB Tools plugin by Bouni"
