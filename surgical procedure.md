# Surgical Procedure metadata

| Subcategory name	| Fieldname |	Use (Required or optional) |	Category (Descriptive, Structural, Administrative)	| General Description |	Type |
| --------	| -------- |	-------- |	--------	| -------- | ---- |
| Surgical Protocol | | | | | |
| | name | required | descriptive | the name of the procedure given by the author | string |
| | description | required | descriptive | the description of the surgical procedure (technique, equipment) or link to protocol | string |
| | author | required | descriptive | the name of the author of this procedure | person |
| | project_id | required | structural | the id of the project this procedure belongs to | string |
| | project_name | optional | descriptive | the name of the project this procedure belongs to | string |
| | version | optional | descriptive | the version of the procedure | string |
| | notes | optional | descriptive | notes about the surgical protocol | string |
| Preoperative Information | | | | | |
| | operator | required | descriptive | the name(s) of the operator(s) | person |
| | purpose  | optional | descriptive | the purpose of the surgery: treatment, prevention, diagnostic, screening, other  | string |
| | location | optional | descriptive | the location of the surgery | string |
| | region | optional | descriptive | the region of the body operated on | string |
| | anesthetic_plan  | optional | descriptive | the agent(s), concentration, dose, route of anesthesia | string |
| | analgesic_plan | optional | descriptive | the agent(s), concentration, dose, route of analgesics | string |
| | date | optional | descriptive | the date of the surgery | various |
| | notes | optional | descriptive | notes about the preoperative info | string |
| Surgical Information | | | | | |
| | duration | required | descriptive | the approximate length of surgery  | float |
| | surgery_start | optional | descriptive | the time the surgery started | float |
| | surgery_end | optional | descriptive | the time the surgery ended | float |
| | specimen_removed | optional | descriptive | the specimen removed from the patient | string |
| | complications | optional | descriptive | the description of any intraoperative complications  | string |
| | survival | optional | descriptive | whether the surgery is non-survival or survival | boolean |
| | notes | optional | descriptive | notes about the surgical info | string |
| Postoperative Information | | | | | |

| Follow-up | | | | | |

| Sample Information | | | | | |

| Surgical Procedure Outcome | | | | | |

[Add your comments or discuss](https://github.com/VH-Lab/neurosciencemetadata/issues/1)


# Metadata from other platforms:

NWB:

odML: 
