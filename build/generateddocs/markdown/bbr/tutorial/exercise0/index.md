
# 0 - Orientation (Schema)

`ogc.bbr.tutorial.exercise0` *v0.1*

Orientation on the structure of Building Blocks

[*Status*](http://www.opengis.net/def/status): Under development

## Description

## Exercise 0 - Orientation

Goal: Understand the mechanics of Building Blocks

Its very easy, but has a few (quite standard) "moving parts".

There are also a **lot** of features and capabilities typical of a specification development and testing cycle that normally require a lot of effort and skills to manage as manual steps, that are integrated into a single workflow - all you need to do is to learn to link these together with the right metadata!

The tutorial will introduce these in a step-wise fashion - feel free to skip ahead - but if something is not clear please go back to the earlier exercises :-).

### Steps
1. Read the [Overview documentation](https://ogcincubator.github.io/bblocks-docs/overview) and answer the following questions to guide your discovery process:
    - How do the underlying [principles](https://ogcincubator.github.io/bblocks-docs/overview/principles) relate to improvement of specifications in your domain? Which best reflect the needs and understandings of your community to improve interoperability?
    - What [types of building blocks](https://ogcincubator.github.io/bblocks-docs/overview/types) do you need to create
    - What types of resources are you starting with?
    - What [registers](https://ogcincubator.github.io/bblocks-docs/overview/registers) contain Building Blocks you can reuse?
    - What technologies do you want to explore (e.g. JSON schema, JSON-LD, SHACL)
1. View the online "build" and "repository" forms of a Building Block register and learn to navigate between the two.  [Watch]()
1. Learn [how to build](https://ogcincubator.github.io/bblocks-docs/build/local) Building Blocks for reuse from source components.
    - note if you cannot run locally you can rely on [github automation](https://ogcincubator.github.io/bblocks-docs/build/github) on your own online fork of this tutorial.
    
    
## Examples

### Reference a local file for examples
[Example from Exercise  1](/bblock/ogc.bbr.tutorial.exercise1/example)

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

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-tutorial/build/annotated/bbr/tutorial/exercise0/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-tutorial/build/annotated/bbr/tutorial/exercise0/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-tutorial](https://github.com/ogcincubator/bblocks-tutorial)
* Path: `_sources/exercise0`

