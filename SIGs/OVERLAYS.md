# The Overlays Special Interest Group (SIG)

This README is a high level abstract for the Overlays Special Interest Group (or SIG) being driven by the OpenAPI Initiative.

Details of the Overlay specification and general discussions can be found on the GitHub repository: 
- [Overlay Specification](https://github.com/OAI/Overlay-Specification/)
- [Discussion (GitHub)](https://github.com/OAI/Overlay-Specification/discussions)

# Charter

The Overlays specification was started to address various edge cases that came out of issues raised in the OpenAPI Specification. As those edge-cases were studied, an opportunity arose to solve them in a general way with the Overlays specification.

Overlays are documents which extend YAML files, and specifically those YAML files that are related to API specifications. 

This extension can be expressed as two parts, a way of targeting nodes within the base YAML file and a mutation of those nodes. With this mechanism it is possible to describe "patches" to the underlying file, that are robust enough to be persisted and governed.

# Current working scope
The Overlays specification is considered ready for experimentation and the goal is to invite prototypes and vendors to test out and validate that their use-cases can be solved. 

The Overlays specification depends on a query language, and the current incumbent (JSONPath) is still be standardized. As a result, prototypes and experiments are encouraged to use existing JSONPath tooling and constraining, where possible, the usage to ignore features that will not make it into the JSONPath IETF standard.

# Future

The result of the current validation will feed into changes that will prepare the Overlays specification for a more general audience. 

At this point the adoption of the specification and a platform to manage its growth will be the key focal points.