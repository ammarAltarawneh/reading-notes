# Dependency Injection & Repository patterns

Dependency Injection (DI) is a design pattern in ASP.NET Core that achieves Inversion of Control (IoC) by abstracting dependencies, registering them in a service container, and injecting them into classes.

Repositories centralize data access logic, providing maintainability and decoupling from the domain model.

SOLID Principles:

1- SRP: Each method/class should have one reason to change.

2- OCP: Software should be open for extension, closed for modification.

3- LSP: Objects can be replaced by derived types without breaking the app.

4- ISP: Use fine-grained interfaces specific to client needs.

5- DIP: Code should depend on abstractions, not concrete implementations.