
# 06 - Import and extend (Schema)

`ogc.bbr.tutorial.exercise6` *v1.0*

Profiling a BBlock from another register

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

* YAML version: [schema.yaml](https://tdn.github.io/bblocks-tutorial/build/annotated/bbr/tutorial/exercise6/schema.json)
* JSON version: [schema.json](https://tdn.github.io/bblocks-tutorial/build/annotated/bbr/tutorial/exercise6/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/tdn/bblocks-tutorial](https://github.com/tdn/bblocks-tutorial)
* Path: `_sources/exercise6`

