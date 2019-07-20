# anylang
By this RFC we are proposing a general framework for microservice applications. anylang is an abstract platform-independent RPC framework separating three essential concerns:
*  Serialization (and deserialization),
*  Communication,
*  Service.

By complying anylang your microservice implementation would be a set of defined services (functions), described by the scheme (data types and function signature), serialization, and communication. This allows you to use different technologies for these different concerns. One might use REST/Sockets/Memory as communication, JSON/XML/ABI as serialization, and Python/Java/C++ as the service.


# Canonical Service Definition


# Implementations
