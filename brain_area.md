# Brain area metadata

| Subcategory name	| Fieldname |	Use (Required or optional) |	Category (Descriptive, Structural, Administrative)	| General Description |	Type |
| --------- | --------- | --------- | --------- | --------- | --------- |
| Metadata for Brain Area | | | | | |
| | brain_area | required | descriptive, structural | the name of the brain area examined | ontology_entry (_NIF-ontology_ -- must be subclassOf or partOf "nervous system") |
| Metadata for Brain Area Relationship | | | | | |
| | experimental_element_id	| required	| structural |	The identifier of the experimental element being referred to	| identifier |
| | relationship	| required	| descriptive |	The relationship between the experimental object and the brain area	| controlled vocabulary: {'Targeted', 'passes through','Verified by histology','Verified by imaging','Verified other'} |



[Add your comments or discuss](https://github.com/VH-Lab/neuroscienceexperimentalmetadata/issues/2)

# Metadata from other platforms:

NWB:

odML: 
