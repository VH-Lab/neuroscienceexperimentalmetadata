# Experimental subject metadata

| Subcategory name	| Fieldname |	Use (Required or optional) |	Category (Descriptive, Structural, Administrative)	| General Description |	Type |
| --------	| -------- |	-------- |	--------	| -------- | ---- |
| Experimental Subject | -------- |	-------- |	--------	| -------- | ---- |
| --------  | subject_id	   |   required| 	structural | a unique identifier for the subject | NEMD Unique identifier |
| --------  | local_identifier | optional	| structural |	identifier for subject within lab or locally	| string |
| Species Identification for Subject | -------- |	-------- |	--------	| -------- | ---- |
| --------  | scientific_name |	required |	descriptive	| the scientific name of the species | ontology scientific name string or "unknown |
| --------  | common_name | optional |	descriptive |	thecommon name of the species	| ontology common name string or "unknown" | 
| -------- |	ontology |	required	| structural | the ontology cited | "NCBI GenBank" (or other valid ontology) |
| -------- |  ontology_id | required | structural | the node or ID of the entry that is cited in the ontology | ontology ID |
| Birth Parameters for Subject | -------- |	-------- |	--------	| -------- | ---- |
| -------- | date_of_birth |	required |	structural, descriptive, and administrative	| the most likely date of birth of the subject | ISO 8601 Date |
| -------- | date_of_birth_earliest |	optional |	structural, descriptive, and administrative	| the earliest possible date of birth of the subject | ISO 8601 Date |
| -------- | date_of_birth_latest |	optional |	structural, descriptive, and administrative	| the latest possible date of birth of the subject | ISO 8601 Date |
| -------- | biological_sex |	required | descriptive and administrative	| the biological sex | sex string or "unknown |
| Physical Measurement for Subject | -------- |	-------- |	--------	| -------- | ---- |
| ________ | timestamp |	required |	structural, descriptive, and administrative	| the time of the measurement | ISO 8601 Date + Time with time zone |
| ________ | weight |	optional | descriptive	| the weight of the subject | number (long double) |
| ________ | timestamp |	required |	structural, descriptive, and administrative	| the time of the measurement | ISO 8601 Date + Time with time zone |





[Add your comments or discuss](https://github.com/VH-Lab/neuroscienceexperimentalmetadata/issues/4)

# Metadata from other platforms:

NWB:

odML: 
