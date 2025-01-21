**[Lecture video available here](https://www.youtube.com/watch?v=2cXgwQA4wVQ&t=2s)**

**Scrum:** Development through iterative sprints that focus on fulfilling requirements. The interaction and constant change brings the need for flexible architecture.

**Software entropy:** As software ages, changes increase the likelihood of errors and bugs.

**Levels of Design**



* System Architecture (very high-level)
    * Main classes and systems
    * Who are the users?
    * Hard to change later
* High Level Design
    * Still hard to change
    * Component interactions
    * Component public interfaces
    * User interaction
    * Component Types:
        * Programs
        * Modules, classes
        * Clients, servers
        * Files, databases
    * Interaction Types:
        * Procedure calls
        * Communication between components
* Low-Level Design
    * Detailed
    * What algorithm or data structure

**Reference Architecture (Web Browser):**



1. User Interface
    1. Display backend
    2. Data persistence
2. Browser Engine
    3. Data persistence
3. Rendering Engine
    4. Networking
    5. JavaScript Interpreter
    6. XML Parser
    7. Display backend

One way dependencies.

**Big Ball of Mud:** No preplanning. Features added one by one. No plans to handle change.

**Architecture Pattern:** Strategy to solve a common organizational problem. Abstract idea omitting implementation details. Ex) peer-to-peer, client-server, layered architecture

**Layered Architecture:** Each layer provides a service to the layer above it. Each layer acts as a client to the layer below it. Awareness does not jump layers. Layers are only accessible to directly neighboring layers. Ex) Operating system, robotics

**Three Tier Architecture:**



* User Interface (Presentation)
    * Calls business logic
    * Does not use data layer
* Business Logic (Controller)
    * Gets and modifies data
* Data
    * Stores data

Updates without changing an interface do not propagate.

**Desirable Attributes:**



* Modularity
    * Loose coupling, high cohesion
* Don’t Repeat Yourself
* Separation of concerns
* Hide design decisions (information hiding)
    * One class should know as little as possible about other systems
* Use of abstraction
* Allow for change and reuse
* Teams can work independently on each component