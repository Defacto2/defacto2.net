Draft JSON data exports for files hosted on Defacto2
==================

#### file/list-json

Will be a 600KB JSON end-point that lists all files hosted on Defacto2. Each object contains URL ID and UUID, ordered by date posted.

Proposed URL:
* www.defacto2.net/file/list-json

#### file/update-json
Will be a 1MB JSON end-point that lists all files hosted on Defacto2. Each object contains URL ID, UUID, updated date/time, created date/time, deleted date/time and is ordered by the date updated.
Of the 3 example objects shown in the JSON document. This first object shows a record that has been updated. The second shows a record that has been deleted. The third shows a record that has been created. The updated value will always be revised when any Create/Update/Delete database action is applied to the record.

Proposed URL:
* www.defacto2.net/file/update-json

#### file/data-json
Contains 3 examples of the file record data exported to a JSON object contained in a document.

Proposed URLs: 
* www.defacto2.net/file/data-json/a82cd5
* www.defacto2.net/file/data-json/ab2d75
* www.defacto2.net/file/data-json/b343ed

##### redundant/file_example.json and redundant/file_example.schema.json 
Are a redundant JSON item example and schema.

##### Validation
JSONlint (http://jsonlint.com/) was used for validation.
