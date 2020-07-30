| Subcategory name	| Fieldname |	Use (Required or optional) |	Category (Descriptive, Structural, Administrative)	| General Description |	Type |
| --------	| -------- |	-------- |	--------	| -------- | ---- |
| Lab metadata | | | | | |
| | name | required | descriptive | name of metadata | string |
| Subject | | | | | |
| | age | required | descriptive | the age of the subject | string |
| | description | optional | descriptive | description of the subject | string |
| | genotype | required | descriptive | genotype of the subject | string |
| | sex | required | descriptive | sex of the subject | string |
| | species | required | descriptive | species of the subject | string |
| | subject_id | required | descriptive | a unique identifier for the subject | string |
| | weight | required | descriptive | weight of the subject | string |
| | date_of_birth | optional | descriptive | datetime of date of birth (can be used instead of age) | string/various |
| NWB File | | | | | |
| | session_description | optional | descriptive | description of the session where this data was generated | string |
| | identifier | required | descriptive | unique identifier for the file | string |
| | session_start_time | required | descriptive | the start date and time of the recording session | string/various |
| | file_create_date | required | descriptive | date and time the file was created | various |
| | timestamps_reference_time | optional | descriptive | date and time corresponding to time zero of all timestamps; defaults to value of session_start_time | various |
| | experimenter | required | descriptive | name of persion who performed experiment | various |
| | experiment_description | required | descriptive | general description of the experiment | string |
| | session_id | required | descriptive | lab-specific ID for the session | string |
| | institution | required | descriptive and administrative | institution(s) where experiment is performed | string |
| | keywords | required | descriptive and administrative | terms to search over | various |
| | notes | optional | descriptive | notes about the experiment | string |
| | pharmacology | required | descriptive and administrative | description of drugs used, including how and when they were administered | string |
| | protocol | required | descriptive | experimental protocol (include IACUC protocol if applicable) | string |
| | related_publications | optional | descriptive | Publication information | various |
| | slices | required | descriptive | Description of slices, including info about preparation thickness, orientation, temperature and bath solution | string |
| | source_script | required | descriptive and administrative | script file used to create this NWB file | string |
| | source_script_file_name | required | descriptive and administrative | name of the source_script file | string |
| | data_collection | required | descriptive and structural | notes about data collection and analysis | string |
| | surgery | required | descriptive | narrative description about sugery, including date(s) and who performed surgery | string |
| | virus | required | descriptive | info about virus(es) used in experiments, including virus ID, source, date made, etc | string |
| | stimulus_notes | required | descriptive | notes about stimuli, such as how and where presented | string |
| | lab | required | descriptive and administrative | lab where experiment was performed | string |
| | acquisition | required | structural? | raw TimeSeries objects belonging to this NWBFile | various |
| | analysis | required | structural | result of analysis | various |
| | stimulus | required | structural | stimulus TimeSeries obects belonging to this NWBFile | various |
| | stimulus_template | required | structural | stimulus template TimeSeries obects belonging to this NWBFile | various |
| | epochs | required | structural | epoch objects belonging to this NWBFile | various |
| | epoch_tags | required | descriptive | sorted lost of tags used across all epochs | various |
| | trials | required | structural | table containing trial data | various |
| | invalid_times | optional | structural | table containing times to be omitted from analysis | various |
| | intervals | required | structural | any TimeIntervals tables storing time intervals | various |
| | units | required | structural and descriptive | a table containing unit metadata | various |
| | processing | required | descriptive | ProcessingModule objects beloning to this NWBFile | various |
| | lab_meta_data | optional | descriptive | extension that contains lab-specific metadata | various |
| | electrodes | required | descriptive and structural | ElectrodeTable that belongs to this NWBFile | various |
| |  | required | descriptive and structural |  | various |
| |  | required | descriptive and structural |  | various |
| |  | required | descriptive and structural |  | various |
| |  | required | descriptive and structural |  | various |
| |  | required | descriptive and structural |  | various |
| |  | required | descriptive and structural |  | various |
| |  | required | descriptive and structural |  | various |
| |  | required | descriptive and structural |  | various |

 
[Add your comments or discuss](https://github.com/VH-Lab/neurosciencemetadata/issues/1)


# Metadata from other platforms:

NWB:

odML: 
