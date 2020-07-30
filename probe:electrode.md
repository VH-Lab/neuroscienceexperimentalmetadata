| Subcategory name	| Fieldname |	Use (Required or optional) |	Category (Descriptive, Structural, Administrative)	| General Description |	Type |
| --------	| -------- |	-------- |	--------	| -------- | ---- |
| all electrode types | | | | | |
| | type | required | descriptive | What type of electrode (ie. sharp, patch, injection, extracellular, multibarrel, mutli-electrode-array, tetrode) | string|
| | impedence | required | descriptive | Electrode impedence | float |
| | resistance | optional | descriptive | Electrode resistance Unit: Ohm | float |
| | manufacturer | optional | administrative | The manufacturer of the electrodes (if ordered from company) | string |
| | probe_maker | optional | administrative | person who made the electrode | string |
| | jig_material | optional | descriptive | the type of material the electrode jig is made of (ie polyethylene, resin, propriatary printing materials) | string |
| | jig_model | optional | descriptive | a model of the jig in a CAD software | file of some sort? |
| | connector | optional | descriptive | what sort of connector is used in the electrode (ex. omnetics with model number) | string |
| | electrode_id | optional | administrative | A unique identifier for the electrode. Custom ID to differentiate electrodes | int |
| | guide_tube_material (guage)?? | optional | descriptive | the type of material the electrode guidetube is made of (polyamide, steel, etc) | string |
| | guide_tube_diameter (guage)?? | optional | descriptive | size of the guide tube | float |
| | channel_count | optional | descriptive | number of channels | float |

[Add your comments or discuss](https://github.com/VH-Lab/neurosciencemetadata/issues/1)


# Metadata from other platforms:

NWB:

odML: 
