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
| N-trodes | | | | | |
| | material | optional | descriptive | The material the electrodes are made of (ie carbon fiber, glass, nichrome) | string |
| | material_manufacturer  | optional | administrative | The manufacturer of the wires the electrodes are made of | string |
| | shape_parameters | optional | descriptive | The shape parameters of the electrode. Describes electrode geometry | array? |
| | tip_size | optional | descriptive | Tip size of electrode | float |
| | coating | optional | descriptive | The coating used to insulate the electrodes | string |
| | electrode_count | optional | descriptive | Number of electrodes in an array | int |
| | tip_coat | optional | descriptive | Coating material used to plate electrode tips (e.g. platinum, gold) | string |
| | final_cut_method | optional | descriptive | How the final length of the tetrode was cut (e.g. fire polishing, cold razor, etc) | string |
| | usage | required | descriptive | What use the electrode serves (ie. ground, reference, channel) | string |
| Glass probes | | | | | |
| | glass_type | optional | descriptive | the type of glass used to create electrodes (quartz, borosilicate) | string |
| | glass_size | optional | descriptive | Inner and outer diameter of glass | string |
| | fire_polish | optional | descriptive | Describes whether electrodes were fire polished | boolean |
| | puller | optional | descriptive | Puller used to make (glass) electrodes | string |
| | pull_parameter | optional | descriptive | Specific pull parameters (ie. heat, trip velocity, heat and cooling duration) | string |
| | electrolyte | optional | descriptive | the type of electrolyte the electrode is filled with | string |

[Add your comments or discuss](https://github.com/VH-Lab/neurosciencemetadata/issues/1)


# Metadata from other platforms:

NWB:

odML: 
