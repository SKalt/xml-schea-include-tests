# xml-schema-include-tests

> a directory of minimal test cases for local XML schema

## **This is a WIP.**

## Layout

```
/xml-schema-include-tests
  |- README.md
  `- fixtures/
      |- spec/ # the
      `- [descriptive-fixture-name]
           |- schema/
           |   |- main.xsd # has imports / excludes
           |   `- *.xsd    # included
           `- expected/
              |- valid/*.xml
              `- invalid/*.xml
```

## Quickstart

### Install

<details open><summary>Via `git submodule`</summary>

<!-- TODO: write this -->

```sh
REPO_URL='git@github.com:SKalt/xml-schema-include-tests.git'
git submodule add $REPO_URL
```

</details>
<details><summary>As a static directory</summary>

<!-- TODO: write this -->

```sh

```

</details>

### Usage

<!--
  TODO: note that file://PATH uris must be adapted, as will xmlns:this="THIS"
-->

### References

You can refer to the XML schema URI for more documentation: https://www.w3.org/2001/XMLSchema

- 1.1
  - [W3C XML Schema Definition Language (XSD) 1.1 Part 1: Structures](http://www.w3.org/TR/xmlschema11-1/)
  - [W3C XML Schema Definition Language (XSD) 1.1 Part 2: Datatypes](http://www.w3.org/TR/xmlschema11-2/)
- 1.0
  - [XML Schema Part 0: Primer (2nd Edition)](http://www.w3.org/TR/xmlschema-0/)
  - [XML Schema Part 1: Structures (2nd Edition)](http://www.w3.org/TR/xmlschema-1/)
  - [XML Schema Part 2: Datatypes (2nd Edition)](http://www.w3.org/TR/xmlschema-2/)
