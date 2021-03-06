# NWB metadata related to electrode

| Subcategory name | Fieldname | Use (Required or optional) | Category (Descriptive, Structuraaal, Administrative) | General Description | Type |
| -------- | -------- | -------- | -------- | -------- | -------- |
| Intercellular Electrode | | | | | |
| | name | required | descriptive & structural | the name of this electrode | string |
| | device | required | descriptive & structural | the device that wasused to record from this electrode | string |
| | description | optional | descriptive | recording description, description of electrode (e.g., whole-cell, sharp, etc.) | string |
| | slice | optional | descriptive | information about slice used for recording | string |
| | seal | optional | descriptive | information about seal used for recording | string |
| | location | required | descriptive | area, layer, comments on estimation, stereotaxis coordinates (if in vivo, etc.) | string |
| | resistance | required | structural | electrode resistance, unit: Ohm | string |
| | filtering | required | structural | electrode specific filtering | string |
| | initial_access_resistance | optional? | structural | initial access resistance | string |
| Extracellular Electrode | | | | | |
| | name | required | descriptive & structural | the name of this electrode | string |
| | description | optional | descriptive | description of this electrode group | string |
| | location | required | descriptive & structural | description of location of this electrode group | string |
| | device | required | descriptive & structural | the device that was used to record from this electrode group | Device |
| | position | optional | descriptive & structural | stereotaxic position of this electrode group (x, y, z) | various (ndarray, list, tuple, Dataset, HDMFDataset, AbstractDataChunkIterator) |
