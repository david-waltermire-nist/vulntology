# Impact Object

An Impact is a recognized result of an Action for a given Vulnerability Scenario. 

## Properties
- **Scope** (one):  A coarse measure of the level of impact an exploit could have on a target. (See [Scope](../values/scope.md)) <br />
- **Criticality** (one): A measure of the relative importance of the associated Scope. (See [Criticality](../values/criticality.md)) <br />

## Types of Impact

- **Logical Impact**: Impacts that occur to the digital aspects of the software. These are considered for assessing traditional notions of confidentiality, integrity and availability.  <br />

    *Type Specific Properties*
  - **hasLogicalImpact** (one): Impacts that occur to the digital aspects of the software. These are considered for assessing traditional notions of confidentiality, integrity and availability. (See [Logical Impact](../values/logical-impact.md))  <br />

  - **Location** (one or many): Designating the specific area or location impacted. Serves as supplemental information (See [Locations](../values/location.md)). <br />
 

- **Physical Impact**: Impacts that occur the tangible aspects of what the software controls or directly influences. Common examples would be damage to assets, people or loss of resources. <br />

  *Type Specific Properties*
  - **hasPhysicalImpact** (one): A tangible impact to a physical device, machinery, the surrounding environment, or people. (See [Physical Impact](../values/physical-impact.md) <br />

