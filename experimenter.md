# Experimenter metadata

| Subcategory name	| Fieldname |	Use (Required or optional) |	Category (Descriptive, Structural, Administrative)	| General Description |	Type |
| --------	| -------- |	-------- |	--------	| -------- | ---- |
| | experimenter | Required | Administrative | Name of persion who performed experiment | ontology_entry (_Ontology1_, _Ontology2_) |
| | institution | Required | Administrative | Institution(s) where experiment was performed | controlled vocabulary |
| | lab | Required | Descriptive and Administrative | Lab where experiment was performed | ontology_entry (_Ontology1_, _Ontology2_) |
| | experimenter_ORCID | Optional | Administrative | ORCID ID of experimenter | string in ORCID format |
| | experimenter_contact information | Required | Administrative | Email, phone number or other contact information about the experimenter | string |

[Add your comments or discuss](https://github.com/VH-Lab/neurosciencemetadata/issues/1)


# Metadata from other platforms:

[NWB](https://github.com/VH-Lab/neuroscienceexperimentalmetadata/blob/master/other_metadata/NWB/experimenter.md)

odML: 
| Subcategory name	| Fieldname | General Description | Type |
| ----- | ----- | ----- | ----- |
| Person |  |  |  |
| | Person | Information about a person. E.g. as Experimenter, Author, etc | string |
| | FirstName | The persons first Name (John) | string |
| | LastName | The persons last name (Doe) | string |
| | FullName | The complete name of this person e.g. John Doe | person |
| | Gender | Male or Female? | string |
| | Birthday | The birthday. YYYY-MM-dd | date |
| | Role | The role of this person e.g. when describing a project (Responsible investigator), or a recording(Experimenter) | string |
| | Email | Person's Email | string |
| | PhoneNumber | Person's phone number | string |
| | Laterality | Handedness - the dominant hand of the subject | string |
| | Education level | Highest archived education level of the person | string |

Metadata from 3D Microscopy Working Group :

| Subcategory name	| Fieldname |	Use (Required or optional) |	Category (Descriptive, Structural, Administrative)	| General Description |	
| --------	| -------- |	-------- |	--------	| -------- |
| Creators |  |	 |	|  |
| | creatorName | Required | Administrative | The creator name - may be Organizational or Personal. Format lastname, firstname |
| | nameType | Optional | Administrative | Controlled Vocabulary: Organizational, Personal |
| | nameIdentifier | Optional | Administrative | Uniquely identifies an individual or legal entity |
| | NameIdentifierScheme | Requried | Administrative | Controlled Vocabulary: ORCID ( Open Researcher and Contributor ID ), ISNI ( International Standard Name Identifier, ROR ( Research Organization Registry ), GRID ( General Repository for Interaction Datasets ) |
| Contributors |  |  |  |  |
| | contributorName | Required | Administrative | The contributor name - may be Organizational or Personal. Format lastname, firstname |
| | nameType | Optional | Administrative | Controlled Vocabulary: Organizational, Personal |
| | nameIdentifier | Optional | Administrative | Uniquely identifies an individual or legal entity |
| | nameIdentifierScheme | Required | Administrative | Controlled Vocabulary: ORCID ( Open Researcher and Contributor ID ), ISNI ( International Standard Name Identifier, ROR ( Research Organization Registry ), GRID ( General Repository for Interaction Datasets ) |
| | contributorType | Required | Administrative | Controlled Vocabulary: Contact Person, Project Leader, Project Member, Researcher, Research Group, Other |


