
# Exercise 6 (Schema)

`ogc.bbr.template.exercise6` *v1.0*

Profiling an external bblock

[*Status*](http://www.opengis.net/def/status): Under development

## Description

## Importing and profiling from an external register

### Steps
- uncomment the import in [bblocks-config.yaml](../../bblocks-config.yaml)
- uncomment the reference to `topo-line` in [schema.yaml](schema.yaml)
- examine the examples and validation reports.



## Examples

### Line with 2 points
#### json
```json
{
  "type": "Feature",
  "id": "LineP1P2",
  "geometry": null,
  "topology": {
    "type": "LineString",
    "references": [
      "P1",
      "P2"
    ]
  },
  "properties": null
}
```

## Schema

```yaml
description: Line with only two points
allOf:
- properties:
    topology:
      properties:
        references:
          minItems: 2
          maxItems: 2

```

Links to the schema:

* YAML version: [schema.yaml](https://raw.githubusercontent.com/ogcincubator/bblocks-tutorial/undefined/build/annotated/bbr/template/exercise6/schema.json)
* JSON version: [schema.json](https://raw.githubusercontent.com/ogcincubator/bblocks-tutorial/undefined/build/annotated/bbr/template/exercise6/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-tutorial](https://github.com/ogcincubator/bblocks-tutorial)
* Path: `_sources/exercise6`

