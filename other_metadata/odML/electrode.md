# NWB metadata related to electrode

| Subcategory name | Fieldname | Use (Required or optional) | Category (Descriptive, Structural, Administrative) | General Description | Type |
| -------- | -------- | -------- | -------- | -------- | -------- |
| All Electrode Types | | | | | |
| | type | optional | descriptive | What type of electrode (i.e., sharp, patch, injection, extracellular, multibarrel, mutli-electrode-array, tetrode) | string |
| | usage | optional | descriptive | Usage of electrode (i.e., round, reference, channel) | string |
| |  material | optional | descriptive | The Material the electrodes are made of e.g. glass. tungsten, steel, etc. | string | 
| | shape parameters | optional | descriptive | The shape parameters of the electrode | string |
| | manufacturers | optional | administrative | The manufacturer of the electrodes if e.g. ordered from a company | string |
| | tipsize | optional | descriptive | Tip size of electrode. Units in micrometers. | float |
| | coating | optional | descriptive | The coating used to insulate the electrodes | string |
| | impedance | optional | descriptive | Electrode impedance. Units in megaohms. | float |
| | electrode count | optional | descriptive | Number of electrodes in a multi-electrode-array | int |
| | description | optional | descriptive | | string |
| Glass Electrode  | | | | | |
| | glass type | optional | descriptive | The type of glass used to pull these electrodes. (e.g. quartz, borosilicate) | string |
| | glass specification | optional | descriptive | Inner and outer diameter, with or without filament | string |
| | fire polish | optional | descriptive | Specifies whether or not the electrodes were fire polished | boolean |
| | puller | optional | descriptive | The puller used to make the electrodes | string |
| | pull parameter | optional | descriptive | The specific pull parameters like heat, trip velocity, heat and cooling duration, etc. | string |
