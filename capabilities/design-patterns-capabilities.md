# Design Patterns Capabilities

Reusable structural and behavioral capabilities the design patterns canon contributes to software systems.

## Creational Capabilities

- **Factory Method** for delegating concrete type selection to subclasses.
- **Abstract Factory** for producing related families of objects.
- **Builder** for assembling complex objects step by step.
- **Prototype** for cloning preconfigured instances.
- **Singleton** for guaranteeing a single coordinated instance (apply with care).

## Structural Capabilities

- **Adapter** for translating between incompatible interfaces.
- **Bridge** for separating abstraction from implementation.
- **Composite** for treating individual and composite objects uniformly.
- **Decorator** for layering behavior at runtime.
- **Facade** for simplifying access to a subsystem.
- **Flyweight** for sharing fine-grained state across many instances.
- **Proxy** for controlling access, lazy loading, or remote invocation.

## Behavioral Capabilities

- **Chain of Responsibility** for passing requests through handlers.
- **Command** for encapsulating actions as objects.
- **Iterator** for sequential traversal without exposing collection internals.
- **Mediator** for coordinating interactions among components.
- **Memento** for capturing and restoring object state.
- **Observer** for one-to-many event notification.
- **State** for varying behavior based on internal state.
- **Strategy** for selecting an algorithm at runtime.
- **Template Method** for defining the skeleton of an algorithm.
- **Visitor** for adding operations to object structures without modifying them.

## API Design Pattern Capabilities

- **Resource** modeling for REST.
- **Pagination, filtering, sorting** for collection navigation.
- **HATEOAS** link discovery.
- **Idempotency keys** for safe retries.
- **Webhook** and **callback** patterns for asynchronous notification.
- **Polling** and **long polling** for state observation.
- **Bulk** operations for batched mutations.
- **Saga** for long-running distributed transactions.

## Cross-Cutting Capabilities

- Shared vocabulary for design discussions.
- Refactoring targets when code violates pattern constraints.
- Teaching scaffolding for new engineers.
- Architectural decision records (ADRs) anchored on named patterns.
