
# Exercise 1 (Schema)

`ogc.bbr.tutorial.exercise1` *v0.1*

Set an example

[*Status*](http://www.opengis.net/def/status): Under development

## Description

## Exercise 1

Goal: take a simple JSON schema and test with an example

### Steps
- un-comment the reference to a local file in [examples.yaml](examples.yaml)
- run build
- run viewer
- navigate to "Exercise 1"
- view validation results at [build-local/...](/register/build-local/tests/bbr/template/exercise1/_report.json)
## Examples

### Reference a local file for examples
[Example from mySchema](../../exercise1/example.json)

In **Markdown** format.
## Schema

```yaml
$schema: https://json-schema.org/draft/2020-12/schema
description: My example schema
type: object
properties:
  a:
    type: string
    format: uri
  b:
    type: number
  c:
    type: number
required:
- a
- b

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-tutorial/build/annotated/bbr/tutorial/exercise1/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-tutorial/build/annotated/bbr/tutorial/exercise1/schema.yaml)

## Sources

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-tutorial](https://github.com/ogcincubator/bblocks-tutorial)
* Path: `_sources/exercise1`

