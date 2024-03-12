---
datapackage:
  title: Dataset Template
  description: A template for a dataset to publish on DataHub. Uses the Data Package metadata.
  licenses:
  - path: http://opendatacommons.org/licenses/pddl/
    title: Open Data Commons Public Domain Dedication and License v1.0
  resources:
  - path: data.csv
    title: C02 PPM per decade
    name: c02-per-decade
    format: csv
    schema:
      fields:
      - name: year
        type: date
      - name: co2
        type: number
---

Here's some text.

You can add as much text as you like.

The data files will be automatically displayed here.

We can add a chart:

<LineChart
  data="./data.csv"
  title="C02 per decade"
  xAxis="year"
  yAxis="co2"
/>

Lorem ipsum dolor sit amet consectetur adipiscing elit molestie parturient nostra dictumst nascetur mollis fames facilisi netus, dis gravida laoreet curabitur ullamcorper bibendum ridiculus aliquam nullam eleifend ut vehicula libero quisque. Nisl quisque primis tortor facilisis consequat suspendisse duis malesuada vel enim fringilla tellus

+ Sociis platea purus bibendum ante sagittis, felis sed gravida nisl.
+ Massa ut viverra vitae suscipit a, velit fames sapien.
+ Hac primis ligula ante ut etiam sodales, eget lobortis leo mi.


