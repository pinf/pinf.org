
# PINF

*PINF is used to model and drive in-ALL-aspects-reactive realtime distributed systems.*

PINF is an

  * Information Model to represent Systems,
  * a Philosophy of Composition and Communication, and
  * a Library of Software Tools

that drive in-ALL-aspects-reactive Realtime Distributed Systems.


## Information Model to represent Systems

### Abstract

It all comes down to the continuum between a principled and functional approach:

  * A **principled approach** favors small primitives applied to **all aspects** to construct a complex system. Note that *all aspects* is truly meant by including *everything involved* in constructing a system from the first action to name the new project folder to every action to build and manipulate the system thereafter.

  * A **functional approach** favors building broader abstractions to reach a goal sooner while loosing potential in the process. Choosing functional over principled is often required as there are no primitives available to model a problem. Other times a functional approach is chosen to save time.

The PINF approach is **rooted in principle** and allows you to build a principled model like a scalable vector graphic with the difference that at any node, PINF can jump to a functional approach to model a subset of the system in that part of the graph to bridge the gap between what is ideal and what is practical.

A system **must be rooted in principle** to be continuously refactorable as only then low-primitives may be manipulated to affect changes in the whole system. If a functional approach is applied it must be manually refactored upon every change.

### Concrete

In a PINF-based system, the system is built from many individual nodes with no central or overreaching tool with authority. Each node knows what it can and cannot do and who it can and cannot talk to but there is no knowledge of the whole in **any** of the parts.

Such a dynamic system becomes difficult to model mentally and thus restrictions and tooling is required to make it visual. Any structure may be created and made visual in numerous ways. The art lies in what to create and how to visualize it so it may be interacted with over time.

Visualization is achieved by having nodes broadcast meta data, collecting such meta data centrally, applying further modeling to it and rendering it dynamically.

### Implementation

The initial **genesis** release of PINF will focus on modeling a system around accepted open technology standards and implement all pieces necessary to build web applications using a **principled first approach**. 


## Philosophy of Composition and Communication

On the **code level** a complete system is made up of [many small components](http://www.quora.com/What-is-the-recommended-method-modularizing-and-packaging-my-web-apps-JavaScript-code/answer/Christoph-Dorn) which are loaded into nested containers using [github.com/pinf/pinf-loader-js](https://github.com/pinf/pinf-loader-js).

Platform adapters are **embedded** into runtimes to provide dynamic containers to run components.

Components may be **networked** using (github.com/kriskowal/gtor)[https://github.com/kriskowal/gtor] principles to allow for spacial and temporal scaling and buffering of data flows. All communication may be cryptographically secured.

All aspects of a system are declared in JSON and woven according to the [orchestration rules](https://github.com/pinf/pinf-config).

On the **physical level** a system is constructed by making provisioning calls to external services, installing runtime containers and booting a minimal communication network.

On the **informational level** a system is a cloud of securely networked nodes that may be interacted with to affect realtime changes in all system aspects.

Most importantly, rather than offering a plethora of features, PINF is focused on selecting a minimal set of concepts and APIs that may be used exclusively to implement and build PINF itself and allow PINF-based systems to expand and contract in every aspect.


## Library of Software Tools

### PINF System Model

  * Communication within: github.com/pinf/pinf-connection
  * Communication without: github.com/firenode

### PINF System Implementation

  * PINF Virtual System: https://github.com/pinf/pinf-vs-js
  * PINF Node Loader: https://github.com/pinf/pinf-loader-js
  * Platform Adapters:
    * Mozilla
    * NodeJS

### PINF System External Environment

  * Ecosystem adapters: github.com/pinf-it

### PINF System Reference Implementations

  * [github.com/devcomp](https://github.com/devcomp)


# PINF Roadmap

* [github.com/devcomp-io](https://github.com/devcomp-io) - A 100% open and hackable **UNIX vm hosted** dev system that can be used for collaborative realtime distributed system development. Built on top of [github.com/pinf-io](https://github.com/pinf-io).
  * 2014 - Phase 1: Prototype and deploy for [firebug.io][http://firebug.io/] only.
  * 2015 - Phase 2: Make available to everyone.

* [github.com/devcomp](https://github.com/devcomp) - A 100% open and hackable **PINF vm hosted** dev system that can be used for collaborative realtime distributed system development. Built on top of [github.com/fireconsole](https://github.com/fireconsole).
  * 2015 - Phase 1: Prototype and deploy for [firebug.io][http://firebug.io/] only.
  * 2016 - Phase 2: Make available to everyone.


# Contribute

Get involved in any of the above projects or financially support anyone working on the them.

