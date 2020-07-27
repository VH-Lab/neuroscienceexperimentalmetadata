# Experimental subject metadata

| Subcategory name	| Fieldname |	Use (Required or optional) |	Category (Descriptive, Structural, Administrative)	| General Description |	Type |
| --------	| -------- |	-------- |	--------	| -------- | ---- |
| Experimental Subject | -------- |	-------- |	--------	| -------- | ---- |
| --------  | subject_id	   |   required| 	structural | a unique identifier for the subject | NEMD Unique identifier |
| --------  | local_identifier | optional	| structural |	an identifier for the subject within the lab or locally	| string |
| Species Identification for Subject | -------- |	-------- |	--------	| -------- | ---- |
| --------  | scientific_name |	required |	descriptive	| the scientific name of the species | ontology scientific name string or "unknown |
| --------  | common_name | optional |	descriptive |	the common name of the species	| ontology common name string or "unknown" | 
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
| ________ | height |	optional | descriptive	| the height of the subject | number (long double) |
| ________ | length |	optional | descriptive	| the length of the subject | number (long double) |
| ________ | age |	optional | descriptive	| the age of the subject | number |
| Metadata for Human Subject | -------- |	-------- |	--------	| -------- | ---- |
| ________ | legal_name |	required | structural	| the legal name of the subject | string |
| ________ | gender |	optional | descriptive	| the gender of the subject | string |
| ________ | email |	optional | administrative	| the birthday of the subject in YYYY-MM-DD format | string |
| ________ | phone_number |	optional | administrative	| the phone number contact info of the subject | string |
| ________ | education_level |	optional | descriptive	| the highest degree earned | string |
| ________ | laterality |	optional | descriptive	| the dominant hand of the subject | string |
| Metadata for Cell Culture | -------- |	-------- |	--------	| -------- | ---- |
| ________ | plate_id |	optional | structural	| a unique identifier for the cell culture | NEMD Unique identifier |
| ________ | culture_kingdom | required | descriptive	| the kingdom the culture belongs to | string |
| ________ | culture_genus | optional | descriptive	| the genus the culture belongs to | string |
| ________ | culture_species | optional | descriptive	| the species the culture belongs to | string |
| ________ | cell_culture | required | descriptive	| whether the cells are in a primary culture, cell line, or cell strain | string |
| ________ | culture_continuity | optional | descriptive	| whether the cell line is finite or continuous | string |
| ________ | culture_conditions | required | descriptive	| a description of the conditions the culture lives in | string |
| ________ | culture_morphology | optional | descriptive	| whether teh culture appears fibroblastic, epethial-like, or lympohoblast-like | string |
| ________ | culture_treatment | optional | descriptive	| a description of any injections or treatments the culture has received | string |
| ________ | plate_time | optional | descriptive	| the time/date that the experimental culture was plated | ISO 8601 Date + Time with time zone |
| Metadata for Individual Cell | -------- |	-------- |	--------	| -------- | ---- |
| ________ | cell_genus | optional | descriptive	| the genus the organism of the recorded cell | string |
| ________ | cell_species | optional | descriptive	| the species of the organism that the recorded cell is in | string |
| ________ | cell_location | optional | descriptive	| the specific location in the organism that the recorded cell is in | string |
| ________ | cell_region | optional | descriptive	| the specific region of the location that the recorded cell is in | string |
| ________ | cell_sub_region | optional | descriptive	| more specification of the region that the recorded cell is in | string |
| ________ | sub_region_layer | optional | descriptive	| the layer of the region that the recorded cell is in | string |
| ________ | cell_structure | optional | descriptive	| the specific part of teh cell that is being recorded | string |
| ________ | identification | optional | descriptive	| description of how the cell was identified | string |















[Add your comments or discuss](https://github.com/VH-Lab/neuroscienceexperimentalmetadata/issues/4)

# Metadata from other platforms:

NWB:

odML: 
