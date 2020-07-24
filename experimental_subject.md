# Experimental subject metadata

| Subcategory name	| Fieldname |	Use (Required or optional) |	Category (Descriptive, Structural, Administrative)	| General Description |	Type |
| --------	| -------- |	-------- |	--------	| -------- | ---- |
| Experimental Subject | -------- |	-------- |	--------	| -------- | ---- |
| --------  | subject_id	   |   required| 	structural | a unique identifier for the subject | NEMD Unique identifier |
| --------  | local_identifier | optional	| structural |	identifier for subject within lab or locally	| string |
| Species Identification | -------- |	-------- |	--------	| -------- | ---- |
| --------  | scientific_name |	required |	descriptive	| the scientific name of the species | ontology scientific name string or "unknown |
| --------  | common_name | optional |	descriptive |	thecommon name of the species	| ontology common name string or "unknown" | 
| -------- |	ontology |	required	| structural | the ontology cited | "NCBI GenBank" (or other valid ontology) |
| -------- |  ontology_id | required | structural | the node or ID of the entry that is cited in the ontology | ontology ID |

[Add your comments or discuss](https://github.com/VH-Lab/neuroscienceexperimentalmetadata/issues/4)

# Metadata from other platforms:

NWB:

odML: 
