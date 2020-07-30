# Experimental subject metadata

| Subcategory name	| Fieldname |	Use (Required or optional) |	Category (Descriptive, Structural, Administrative)	| General Description |	Type |
| --------- | --------- | --------- | --------- | --------- | --------- |
| Metadata for All Subjects | | | | | |
| | subject_id	   |   required| 	structural | a unique identifier for the subject | NEMD Unique identifier |
| | local_identifier | optional	| structural |	an identifier for the subject within the lab or locally	| string |
| Species Identification for Subject | | | | | |
| | species |	required |	descriptive	| the species identifier | ontology_entry (_NBCI Genebank_ -- species identifer) |
| Birth Parameters for Subject | | | | | |
| | date_of_birth |	required |	structural, descriptive, and administrative	| the most likely date of birth of the subject | ISO 8601 Date |
| | date_of_birth_earliest |	optional |	structural, descriptive, and administrative	| the earliest possible date of birth of the subject | ISO 8601 Date |
| | date_of_birth_latest |	optional |	structural, descriptive, and administrative	| the latest possible date of birth of the subject | ISO 8601 Date |
| | biological_sex |	required | descriptive and administrative	| the biological sex | sex string or "unknown |
| Physical Measurement for Subject | | | | | |
| | timestamp |	required |	structural, descriptive, and administrative	| the time of the measurement | ISO 8601 Date + Time with time zone |
| | weight |	optional | descriptive	| the weight of the subject | number (long double) |
| | height |	optional | descriptive	| the height of the subject | number (long double) |
| | length |	optional | descriptive	| the length of the subject | number (long double) |
| | width |	optional | descriptive	| the width of the subject | number (long double) |
| | age |	optional | descriptive	| the age of the subject | number |
| Metadata for Human Subject | | | | | |
| | gender |	optional | descriptive	| the gender of the subject | ontology_entry (_Ontology1_, _Ontology2_) |
| | race | optional | descriptive | the race of the subject | ontology_entry (_Ontology1_, _Ontology2_) |
| | nationality | optional | descriptive | the nationality of the subject | ontology_entry (_Ontology1_, _Ontology2_) |
| | education_level |	optional | descriptive	| the highest degree earned | ontology_entry (_Ontology1_, _Ontology2_) |
| | laterality |	optional | descriptive	| the dominant hand of the subject | ontology_entry (_Ontology1_, _Ontology2_) |




Very early draft:
| Metadata for Cell Culture | |	|	| | |
| | plate_id |	optional | structural	| a unique identifier for the cell culture | NEMD Unique identifier |
| | culture_kingdom | required | descriptive	| the kingdom the culture belongs to | string |
| | culture_genus | optional | descriptive	| the genus the culture belongs to | string |
| | culture_species | optional | descriptive	| the species the culture belongs to | string |
| | cell_culture | required | descriptive	| whether the cells are in a primary culture, cell line, or cell strain | string |
| | culture_continuity | optional | descriptive	| whether the cell line is finite or continuous | string |
| | culture_conditions | required | descriptive	| a description of the conditions the culture lives in | string |
| | culture_morphology | optional | descriptive	| whether teh culture appears fibroblastic, epethial-like, or lympohoblast-like | string |
| | culture_treatment | optional | descriptive	| a description of any injections or treatments the culture has received | string |
| | plate_time | optional | descriptive	| the time/date that the experimental culture was plated | ISO 8601 Date + Time with time zone |
| Metadata for Individual Cell | | | | | |
| | cell_genus | optional | descriptive	| the genus the organism of the recorded cell | string |
| | cell_species | optional | descriptive	| the species of the organism that the recorded cell is in | string |
| | cell_location | optional | descriptive	| the specific location in the organism that the recorded cell is in | string |
| | cell_region | optional | descriptive	| the specific region of the location that the recorded cell is in | string |
| | cell_sub_region | optional | descriptive	| more specification of the region that the recorded cell is in | string |
| | sub_region_layer | optional | descriptive	| the layer of the region that the recorded cell is in | string |
| | cell_structure | optional | descriptive	| the specific part of teh cell that is being recorded | string |
| | identification | optional | descriptive	| description of how the cell was identified | string |















[Add your comments or discuss](https://github.com/VH-Lab/neuroscienceexperimentalmetadata/issues/4)

# Metadata from other platforms:

NWB:

odML: 
