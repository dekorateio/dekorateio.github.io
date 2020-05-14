---
layout: base
---

Dekorate is a collection of compile time generators and decorators of Kubernetes manifests.
It makes generating and decorating Kubernetes manifests as simple as adding a dependency to your project.
No editing of xml, yml or json is required. Everything is done via:

- The standard configuration mechanism of your framework.
- Java annotations.
- Auto adapting to your code.

And the best part is that its language and build tool independant!

### Features
- Generates manifest via annotation processing
  - [Kubernetes](kubernetes/index.md){:target="_blank"}
  - [OpenShift](openshift/index.md){:target="_blank"}
  - Knative
  - Tekton
- Rich framework integration
  - Generic Java 
  - Spring Boot
  - Quarkus
  - Throntail
- junit5 integration testing extension
  - Kubernetes
  - Openshift

### A quick view

It's always helps to see something in action before you dive into the docs:

![asciicast](assets/images/dekorate-spring-hello-world.gif "Dekorate Spring Boot Hello World Asciicast") 


### Want to learn more?

- [Getting Started](getting-started)
- [Docs](dekorate){:target="_blank"}
- [Sources](https://github.com/dekorateio/dekorate){:target="_blank"}
