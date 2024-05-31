---
datapackage:
  title: Dataset Template
  description: A template for a dataset to publish on DataHub. Uses the Data Package metadata.
  licenses:
  - path: http://opendatacommons.org/licenses/pddl/
    title: Open Data Commons Public Domain Dedication and License v1.0
  resources:
  - path: iris.csv
    title: Iris dataset
    name: iris
    format: csv
    schema:
      fields:
      - sepal.length : number
      - sepal.width : number
      - petal.length : number
      - petal.width : number
      - variety : text
        
---

Here's some text.
