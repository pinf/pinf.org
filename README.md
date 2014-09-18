
# PINF

*PINF is used to model and drive in-ALL-aspects-reactive realtime distributed systems.*

PINF is an

  * Information Model to represent Systems,
  * a Philosophy of Composition and Communication, and
  * a Library of Software Tools

that drive in-ALL-aspects-reactive Realtime Distributed Systems.


## Information Model to represent Systems

WIP: 2015


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

## 2014

  * [github.com/devcomp-io/devcomp](https://github.com/devcomp-io/devcomp) - A 100% open and hackable **UNIX vm hosted** dev system that can be used for collaborative realtime distributed system development.

## 2015

  * [github.com/devcomp/devcomp](https://github.com/devcomp/devcomp) - A 100% open and hackable **PINF vm hosted** dev system that can be used for collaborative realtime distributed system development.


# Contribute

Get involved in any of the above projects or financially support anyone working on above the projects.

