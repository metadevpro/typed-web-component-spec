# The Typed Web Components Specification

The **Typed Web Components Specification** is a community-driven proposal for standarization on typing the public interface exposed by Web Components. 

## Versions

| Version | Date       | Description     | State |
|:-------:|:-----------|:----------------|:-----:|
| [0.1](versions/0.1.md)     | 2018.11.25 | Initial version | Working draft |


## Necessity
**Web Components** are a great technology standarized by W3C and implemented by mayor browsers.

We, as Web Component users and tools authors [[1]](https://medium.com/@pjmolina/quid-6d89b0ec58d5), think we need to provide type information to be able to implement the following uses cases, important for Web Component massive market adoption:

1. Automatic discovery and import of 3rd party web components based on type info.
2. Automatic validation of type errors when using a web component.
3. Standarize documentation about Web Component and usage.

## Discussion
On one side, innertia on the JavaScript tends to expose properties, method and parameters untyped.
Typed are resolved ar runtime based on the implemented component.

On the other hand, previous experiences in component based systems and composition make quite evident that a central catalog to publish, discover and documentation make easier for customers to consume such components.

Therefore, despite the language used to implement a web component (typed or untyped), we strongly thing types are a very valuable information for consumers.

This information will enable the following scenarios:

1. Automatic import a new web component to a palette of componnent for design and composition.
2. Code completion in editors (IDEs).
3. Validation in editors (IDE) type checking.

## Proposal

Therefore, to enable these scenarios, a proposal for typing web components is provided.

Anyone wanting to type its component will benefict from tooling been able to spread the usage of the components.
This typing information is used in desing-time on tooling and totally erased on run-time making a zero performace on production code.


## References

1. [Quid. A tool for composing Web Components](https://medium.com/@pjmolina/quid-6d89b0ec58d5)

## Authors

  - Dr. Pedro J. Molina [@pjmolina](https://github.com/pjmolina)

## License

The full specification is licensed under the Apache 2.0 Licence.
