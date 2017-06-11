# mgnlq_testmodel

test model data
for the mongo db based nlq processing

contains
  1. Mongoose schema  <modelname>.mongooseschema.json
  2. Model documents (which are effectively model data loaded into mongoose)  <modelname>.doc.json
  3. <modelname>.data.json


Filename              |   | comment
----------------------|---|------------
model.json            |   |
<modelname>.doc.json  | Model Documents | data effectively loaded into mongodb  "models" collection
<modelname>.mongooseschema.json |
<modelname>.data.json |   |



## How to use

The data can be uploaded into a mongodb  ("testdb")
via  [mgnlq_model](https://github.com/jfseb/mgnlq_model)

```npm run load_data```