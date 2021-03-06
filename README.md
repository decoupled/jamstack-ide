----

This README is aspirational - The plan is to use [Decoupled Studio](https://marketplace.visualstudio.com/items?itemName=decoupled.studio) and the work with Redwood.js' IDE support as a starting point

----

# JAMStack IDE

* The JAMStack IDE Is a VSCode Extension that provides high-quality support for a set of technologies, services and frameworks that adhere to the JAMStack architecture.
* More importantly, the JAMStack IDE enables a set of **high-productivity workflows** that leverage the JAMStack's Git based approach for CI/CD

# JAMStack Workflows

The main reason we're building the JAMStack IDE and adding support for all the frameworks and technologies is to enable the JAMStack Workflows.

* In one click, the IDE enters a "workflow mode". In this mode you can just code, and you're guided by a visual aid.


# Framework Features

* Frameworks:
  * Redwood.js, Next.js, Gatsby.js, Nuxt, Svelte, ...
* Clouds
  * Netlify
* DB related
  * FaunaDB
  * Prisma
* APIs
  * Contentful
* ...

## Redwood.js

...

## Netlify

* 
* Manage almost every aspect of your account and sites right from the IDE

## Next.js

## Why did we build this?

Sort answer:
* To make the JAMStack experience better for everyone!

Longer answer:

As of august 2020, the quality of VSCode extensions related to the JAMStack is not ideal.
This is due, in part, to the following reasons:

* Writing VSCode extensions is hard and time consuming
* Writing VSCode extensions sometimes requires specialized knowledge that might not be present in the core team behind a particular framework
* Keeping the developer experience consistent across multiple extensions is hard. This is critical, since most JAMStack projects combine multiple different technologies

The JAMStack IDE addresses all of these issues in the following ways:

* **Leadership and coordination** - a central effort with a clear goal in mind: High quality experience across the board
* **An SDK and simple architecture** that provides a common foundation for extensions (built on top of the Language Server Protocol)
* A set of higher-level features (on top of the basic VSCode language features) that extensions can implement (for example: lifecycle management, preview, issuing auth tokens, etc)

# Contributing to the JAMStack IDE

* If you are working on a web framework, API service, CSS library, etc that you believe adheres to the JAMStack architecture

## Language Servers and The JAMStack IDE SDK

* Contributions to the IDE have two parts
  * You can add some logic to the main extension here
  * Your framework can contribute a Language Server that uses an extended version of the Language Server Protocol

### Diagnostics and Language Features

* Diagnostics and Language features are provided by a Language Server that you implement, and publish, alongside your framework.


### Project Outline, Lifecycle, Preview and others


# FAQ

* I can write VSCode extensions. Why would I build an extension for the JAMStack IDE?

# LSP extensions

## Diagnostic and Language Features

Leverages the Language Server Protocol.

## Project Outline

## Lifecycle, Preview

## Auth tokens and accounts

## Future

* Bidirectional navigation between rendered webpage and code
  * We already implemented this for magic and partially for Next.js. It will be slightly different for every framework. The end result, when coupled with Netlify Dev for example, can completely change the development experience.


