# Development proposal for KiCAD support script

* From: Hotte
* To: Sherry, Daisy, and Kevin


## Community sources research

At this point of Feb 2022, there're 4 plugins that generates JLCPCB-compitible fabrication files. <br/>
The following table shows them in comparison. <br/>
As the GitHub statistics shows, [Bouni's plugin](https://github.com/Bouni/kicad-jlcpcb-tools) is the most matured project. <br/>
I didn't test them all by myself. <br/>
But I'm sure [Bouni's plugin](https://github.com/Bouni/kicad-jlcpcb-tools) will solve desginer's issue mostly.

GIthub Repository | Author | Star | Fork | Contributors | Last Updated
------------------|--------|------|------|--------------|-------------
[KiCAD JLCPCB tools](https://github.com/Bouni/kicad-jlcpcb-tools) | Bouni bouni@owee.de | 244 | 28 | 10 | Feb 2022
[KiCad JLCPCB BOM Plugin](https://github.com/wokwi/kicad-jlcpcb-bom-plugin) | Wokwi <https://wokwi.com/> | 110 | 25 | 3 | 2021
[KiJLC](https://github.com/fullyautomated/KiJLC) | Fully Automated <https://fully.automated.ee/> | 12 | 8 | 2 | 2021
[KiCad BOM CPL Plugin](https://github.com/prrvchr/KiCad-BOM-CPL-Plugin) | prrvchr prrvchr@gmail.com | 3 | 2 | 1 | 2020

## Something better than [Bouni's plugin](https://github.com/Bouni/kicad-jlcpcb-tools)?

Here're the features I am thinking a new plugin (if we're gonna really make it) can offer. <br/>
To accoplish these, it's good to have an access to the JLCPCB's part search API.

1. strightforward and easy way single button for direct JLCPCB orderign from KiCAD.
2. auto-filling most BOM elements such as resistors and capacitors, <br/>
based on JLCPCB stock availability, basic/extended part library, and unit cost.

## The big question

But, do we really need to re-develop the plugin while there's already a good one - [Bouni's plugin](https://github.com/Bouni/kicad-jlcpcb-tools)?
