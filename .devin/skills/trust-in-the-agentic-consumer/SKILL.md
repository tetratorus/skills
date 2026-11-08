---
name: trust-in-the-agentic-consumer
description: Apply when designing or writing tools, skills, APIs, wrappers, or reference material likely to be consumed by an agent. Trust the agentic consumer by leaving room to discover capabilities and uses rather than force-fitting a workflow or user-facing interface.
triggers:
  - model
---

# Trust In The Agentic Consumer

Design for a consumer that can discover how to use what you give it. Do not pre-decide all the ways it should be used.

The point is not merely to leave room for reasoning within a workflow you have already chosen. Leave room for discovery: of the tool, its capabilities, the underlying material, and uses you did not anticipate.

## Expose what exists

Give the agent a useful entry point and enough context to orient itself: what the resource is, where it lives, and where its capabilities can be discovered. Existing help, source, schemas, examples, and inspectable data can carry the detail.

Describe the actual resource rather than narrowing it to the first task that motivated its creation. A screen-history archive is a resource an agent can explore, not necessarily a “summarize my last hour” command.

## Do not substitute your imagined workflow for discovery

Avoid adding wrappers, fixed argument templates, mandatory sequences, exhaustive use-case lists, or prescribed output formats merely because a human-facing product might need them. Do not make the user learn a special invocation when the agent can discover and use the capability from ordinary task context.

An existing tool interface can be sufficient. A skill can simply explain that something exists and point to it. Examples can reveal a capability without defining the only legitimate way to use it.

Add structure when the underlying system or the user's actual requirement needs it, not to constrain the agent to your prediction of its next move.

## Make discovery possible, not mysterious

Trust is not an excuse for opaque tools or missing information. Expose meaningful names, discoverable capabilities, understandable results and errors, and material constraints such as side effects or data limitations. Keep factual contracts precise while leaving possible uses open.

Preserve authorization, privacy, validation, and destructive-operation safeguards. Trust in discovery does not expand the consumer's permissions.

The design test: **Can an agent discover what this offers and use it for a purpose I did not script?** If the consumer has to follow the author's imagined interaction to reach the underlying capability, reconsider that extra structure.
