# Requirements

## [[COMP-ENGINE]]

- [[REQ1-1]]: The Engine shall manage [[type|types]] and the lifecycle of [[instance|instances]] and [[link|links]].

## [[COMP-CLI]]

- [[REQ2-1]]: The CLI shall provide a command line API for interacting the [[COMP-ENGINE]].
- [[REQ2-2]]: The CLI shall enable ingestion of models via data source plugins.
- [[REQ2-3]]: The CLI shall be extendable with data source plugins.

## [[COMP-CLI-MD]] 

- [[REQ3-1]]: The CLI Plugin MD shall serialize git-architect [[type|types]], [[instance|instances]] and [[link|links]] from markdown
- [[REQ3-1-1]]: The CLI Plugin MD shall support all [[instance-definition-strategies]]