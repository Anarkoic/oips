OIP Number   | < Creator must leave this blank. Editor will assign a number.>
:-------------|:----
Title         | <Keep succinct. Maximum 44 characters.>
Description   | <A short, single-sentence description of this OIP. Maximum 140 characters.>
Author        | <Name, along with Keybase handle or GitHub address, of each author, separated by a comma.>
Editor        | < Creator must leave this blank. Editor will be assigned.>
Comments-URI  | < Creator must leave this blank. Editor will assign a URI.>
Status        | < Creator must leave this blank. Editor will assign a status.>
Category      | <Standards Track \| Process \| Informational>
Sub-Category  | < Add according to Category>
Created       | <Date created, using yyyy-mm-dd format (ISO 8601)>
Requires      | <OIP number(s), (optional)>
Replaces      | <OIP number, (optional)>
Superseded-By | <OIP number (only allowed for Obsolete OIPs)>

This is the template for all OIPs to use. Please fill it out according to the guidelines laid out in [OIP001](/OIPs/OIP-0001.md). All media associated with this OIP should be added to the `assets/OIP-<OIP>` folder, which you may create after you receive your OIP number.

Copy the template file to the `OIPs` folder, rename it to `OIP-<your name>-<your proposal>`, fill it out, and submit it as a pull request.

## Abstract
Give a single-paragraph description of your proposal. The abstract should stand on its own -- someone who reads it should be able to understand the gist of your proposal without reading anything else.

## Motivation
Describe why you are creating this proposal. Make sure to include:
  * What problem are you trying to solve?
  * How would this proposal benefit Ord's overall ecosystem?
  * What are the use cases for this proposal?
  * How technically feasible will this be to implement?

This section is especially critical if you are proposing changes to Ord's core protocols. It should clearly answer all of the above, as well as explain exactly why the current protocol is inadequate.

## Backwards Compatibility
If your proposal has any backwards incompatibilities, you must list them here. Make sure to include:
  * Which aspects of your proposal are not backwards compatible?
  * Which alternatives did you consider, and why did you not propose them?
  * How severe are the incompatibilities introduced?
  * How does your proposal address these incompatibilities?

## Rationale
Describe the reasons for designing your features in the way you have proposed. Make sure to include:
  * Why did you choose your design?
  * What design decisions did you make?
  * What alternative designs did you consider?
  * How have you achieved community consensus for your design? Provide links to discussions if available.
  * What objections were raised during your discussions with the community, and how does your design address them?

## Specification
List the full technical design specification of any new feature you are proposing. This must include details of all syntax and semantics required to implement each new feature.

This section should be _detailed_. It needs to allow for competing interoperable implementations. When applicable, it may include technical diagrams to accompany your design.

## Test Cases
  * Most Standards Track proposals will require a suite of test cases, which you may add to the `assets/OIP-<OIP>` folder.
  * Some Process proposals will require test cases, depending on the significance of new features being added.
  * Informational proposals typically will not require test cases.

Your proposal will have a greater chance of success if you err on the side of including more test cases. Use your best judgment.

## Reference Implementation
Most Standards Track proposals, as well as some Process proposals, also will require a reference implementation to be included. It should be added to the same folder as your test cases, `assets/OIP-<OIP>`.

Regardless of this proposal's category, the reference implementation does not need to be completed in order to move the OIP into _Draft_. However, it must be provided before the OIP can be moved into _Review_.

## Security
This section is mandatory for all OIPs. List all considerations relevant to the security of this proposal if it is implemented. This section may be modified as the proposal moves toward consensus. Make sure to include:
  * Security-related design decisions
  * Important discussions
  * Any security-related guidance
  * All threats and risks, as well as how you are addressing them

## Additional Assets
Give a listing of files associated with this OIP. This list will be added upon as the OIP moves along the process of approval. All new files should be added to the `assets/OIP-<OIP>` folder. You should link to each individual file here, using relative links.

## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

This tempplate is based on the [CHIP template](https://github.com/Chia-Network/chips/blob/main/chip-template.md)



