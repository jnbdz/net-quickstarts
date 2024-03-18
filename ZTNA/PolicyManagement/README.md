# Policy Management | ZTNA | Net | Quickstarts

## Terminology
Non-normative terminology (following [RFC 2904](https://datatracker.ietf.org/doc/html/rfc2904), except for PAP): 

| Abbr. | Term                       | Description                                                                                                                                                  |
|-------|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| PAP   | Policy Administration Point | Point which manages access authorization policies                                                                                                           |
| PDP   | Policy Decision Point      | Point which evaluates access requests against authorization policies before issuing access decisions                                                        |
| PEP   | Policy Enforcement Point   | Point which intercepts user's access request to a resource, makes a decision request to the PDP to obtain the access decision, and acts on the received decision |
| PIP   | Policy Information Point   | The system entity that acts as a source of attribute values (i.e., a resource, subject, environment)                                                         |
| PRP   | Policy Retrieval Point     | Point where the XACML access authorization policies are stored, typically a database or the filesystem                                                      |

## Documents
- [RFC 2904 [pdf]](./Documents/rfc2904.txt.pdf)
  - [RFC 2904 [txt]](./Documents/rfc2904.txt)
    - Source: https://www.rfc-editor.org/info/rfc2904
