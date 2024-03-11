---
layout: ontology_detail
id: radx
title: RADx-demo
jobs:
  - id: https://travis-ci.org/ckindermann/radx-demo
    type: travis-ci
build:
  checkout: git clone https://github.com/ckindermann/radx-demo.git
  system: git
  path: "."
contact:
  email: 
  label: 
  github: 
description: RADx-demo is an ontology...
domain: stuff
homepage: https://github.com/ckindermann/radx-demo
products:
  - id: radx.owl
    name: "RADx-demo main release in OWL format"
  - id: radx.obo
    name: "RADx-demo additional release in OBO format"
  - id: radx.json
    name: "RADx-demo additional release in OBOJSon format"
  - id: radx/radx-base.owl
    name: "RADx-demo main release in OWL format"
  - id: radx/radx-base.obo
    name: "RADx-demo additional release in OBO format"
  - id: radx/radx-base.json
    name: "RADx-demo additional release in OBOJSon format"
dependencies:
- id: hp
- id: mondo
- id: nbo
- id: ncit
- id: pato
- id: symp

tracker: https://github.com/ckindermann/radx-demo/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
activity_status: active
---

Enter a detailed description of your ontology here. You can use arbitrary markdown and HTML.
You can also embed images too.

