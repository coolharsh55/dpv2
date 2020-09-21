# dpv2

hard fork of [DPV](https://github.com/dpvcg/dpv) consisting of some experimental changes

## Changes

- applied correct `xsd:date` datatype
- removed several triples for conformance with OWL2-DL, OWL2-QL, OWL2-RL, OWL2-EL, and OWL2-Full
  - removed `xsd:boolean` as range / datatype
  - removed assertions of range containing OWL union of concepts
- fixed source to "DPVCG" where it was "s"