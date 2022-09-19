# The Travel Special Interest Group (SIG)

This readme contains some high level information on the OpenAPI Initiative special interest group for workflows.

Full details on the Travel SIG and to get involved, check out:
- [repo](https://github.com/OAI/sig-workflows)
- [slack](https://open-api.slack.com/archives/C022K8VD7AP)

## Charter / Motivation / Mission

Being able to express specific sequences of calls and articulate the dependencies between them to achieve a particular goal is desirable in the context of an API specification. Our aim is to propose an enhancement to the current OpenAPI, or accompanying specification (or means), that can define sequences of calls and their dependencies to be expressed in the context of delivering a particular outcome or set of outcomes.

The creation of the SIG-Workflows group is inspired by the need to store sequences of calls in the context of specific tests, and in order to communicate the particulars of a complex set of security related calls such as when using OAuth2 and the Financial-grade API security profile of OpenID Connect.

However, such a definition will be useful for understanding how to implement any dependent sequence of functional calls for any user of Open API such as authorization calls, redirects and web hooks in order to achieve a certain technical or functional outcome.

Optimally, it should be possible to articulate these workflows in a human and machine readable manner, thus improving the capability of API specifications to tell the story of the API in a manner that can improved the consuming developer experience and understanding of an API specified using OpenAPI.

## Current Working Scope

- **Context** - How to define quickly and easily what goal and key functions of an API are, and how to represent that in a specification
- **Workflows** - Handling key and complex sequences which may involve the reuse of endpoints for multiple uses, like token calls in a FAPI compliant sequence, in both a human and machine readable way, supporting both understanding and automation
- **Tooling** - How to best integrate to tools and provide machine readable context for those tools so that the spec can integrate with the tools used by developers

## Future Plans
Formalize draft spec and sample tooling implementation to present towards the OpenAPI Technical Steering Committee (TSC).
