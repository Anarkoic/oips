OIP Number    | 
:-------------|:----
Title         | Extensible Inscription Headers
Description   | A HTTP-influenced approach to extensible headers in Ordinal Inscriptions
Author        | Anarkoic
Editor        | 
Comments-URI  | 
Status        | 
Category      | TODO <Standards Track \| Process \| Informational>
Sub-Category  | TODO < Add according to Category>
Created       | 2023-06-14
Requires      | 
Replaces      | 
Superseded-By | 


## Abstract
An extensible way to support additional headers in Ordinal Inscriptions beyond the content type. In particular, this can be used to support compression.

## Motivation

Biggest motivation is to improve utilization of blockspace by adding support for compression. In the interest of reusing 
existing approaches, we proposed using an HTTP-style approach. Which in turn motivates having this as a flexible design rather 
than a compression-only solution.

## Backwards Compatibility

Past Inscriptions are supported and no change is needed for them.

Explorers will need to be updated to handle new Inscriptions using this approach.

## Rationale


## Specification

After the initial OP_PUSH 1 following by OP_PUSH content-type, additional pairs of OP_PUSH 1 and OP_PUSH text can be added, where text is a valid HTTP header, per IETF RFC 9110 HTTP Semantics https://www.rfc-editor.org/rfc/rfc9110.html.

Example:

OP_FALSE
OP_IF
  OP_PUSH "ord"
  OP_PUSH 1
  OP_PUSH "text/plain;charset=utf-8"
  OP_PUSH 1
  OP_PUSH "Content-Encoding: gzip"
  OP_PUSH 1
  OP_PUSH "X-Other-Header: ordiordiordi"
  OP_PUSH 0
  OP_PUSH "Hello, world!"
OP_ENDIF


## Test Cases
TO DO 

## Reference Implementation
Example given above

## Security
TODO

## Additional Assets
N/A

## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).




