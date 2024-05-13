---
datapackage:
  title: Glycemic Index and Glycemic Load of common foods
  description: This is an overview of the glycemic index and the glycemic load of the common foods. 
  licenses:
  - path: http://opendatacommons.org/licenses/pddl/
    title: Daniela Popova license 
  resources:
  - path: high-gi-foods.csv
    title: High Glycemic Index foods
    description: list of some common high glycemic index foods
    name: high-gi-foods
    format: csv
    schema:
      fields:
      - name: Foods
        type: string
      - name: GI
        type: number
  - path: high-gl-foods.csv
    title: High Glycemic Load foods
    description: list of some common high glycemic load foods
    name: high-gl-foods
    format: csv
    schema:
      fields:
      - name: Foods
        type: string
      - name: GL
        type: number
  - path: medium-gi-foods.csv
    title: Medium Glycemic Index foods
    name: medium-gi-foods
    description: list of some common medium glycemic index foods
    format: csv
    schema:
      fields:
      - name: Foods
        type: string
      - name: GI
        type: number
  - path: medium-gl-foods.csv
    title: Medium Glycemic Load foods
    name: high-gl-foods
    description: list of some common medium glycemic load foods
    format: csv
    schema:
      fields:
      - name: Foods
        type: string
      - name: GL
        type: number
  - path: low-gi-foods.csv
    title: Low Glycemic Index foods
    name: low-gi-foods
    description: list of some common low glycemic index foods
    format: csv
    schema:
      fields:
      - name: Foods
        type: string
      - name: GI
        type: number
  - path: low-gl-foods.csv
    title: Low Glycemic Load foods
    name: high-gl-foods
    description: list of some common low glycemic load foods
    size: 1MB
    format: csv
    schema:
      fields:
      - name: Foods
        type: string
      - name: GL
        type: number
---

# glycemic-index-vs-glycemic-load-foods



## Definitions

TODO

## Glycemic index vs glycemic load

TODO

## Glycemic index of the common foods

<FlatUiTable
  data={{
    url: 'overview-gi.csv'
  }}
 />

<FlatUiTable
  data={{
    url: 'low-gi-foods.csv'
  }}
 />

 <FlatUiTable
  data={{
    url: 'medium-gi-foods.csv'
  }}
 />

 <FlatUiTable
  data={{
    url: 'high-gi-foods.csv'
  }}
 />

## Glycemic load of the common foods

<FlatUiTable
  data={{
    url: 'overview-gl.csv'
  }}
 />

<FlatUiTable
  data={{
    url: 'low-gl-foods.csv'
  }}
 />

 <FlatUiTable
  data={{
    url: 'medium-gl-foods.csv'
  }}
 />

 <FlatUiTable
  data={{
    url: 'high-gl-foods.csv'
  }}
 />

## Source

This data comes from Verywellhealth: https://www.verywellhealth.com/glycemic-index-chart-for-common-foods-1087476

