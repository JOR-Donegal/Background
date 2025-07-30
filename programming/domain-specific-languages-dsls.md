# Domain Specific Languages (DSLs)

The computer languages we have considered so far, are all _general-purpose languages_ (GPLs). In some cases, we have languages which are specialized for use in a specific domain. These are _domains specific languages_ (DSLs) \[1].

A simple example might be REGEX. It exists as part of many other languages (such as Python), as it is parsed independently of the host general purpose language it is referred to as an external DSL. Cascading Style Sheets (CSS) as used with HTML is another example.

Internal DSLs are more like an API in a host general purpose language. SQL is another commonly used example.

Ansible is used to configure devices and uses its own syntax.

When I'm working with Internet of Things (IoT), many systems have unique DSLs specifically for their own functionality.

\[1] Fowler, M., 2010. Domain-specific languages. Pearson Education
