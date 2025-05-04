# ARCHITECTUAL OPTIONS CONSIDERED

## Componen-based pattern
Component based architecture is Unity’s core design style and involves building game objects by attaching modular components that are each responsible for a specific function. This architecture encourages separation of concerns which makes code easier to manage and debug. It can also be reused across various game objects to reduce redundancy and offers flexible and rapid prototyping, allowing components to be added or removed as needed.

## Inheritance
Inheritance architecture allows a class to inherit certain properties and methods from another class which helps reduce duplication of code. However, the overuse of inheritance can sometimes lead to a rigid and inflexible code structure. This type of architecture should be use in conjunction with other architectural types.

## Interfaces
Interfaces would allow shared logic to be written once and be applied to multiple character types, enhancing modularity and code reusability. Changes to behaviours can be made in one place which would reduce the risk of inconsistencies. While reusability and flexibility has its advantages, using interfaces in the architectural structure does increase the learning curve for new developers due to the added layer of abstraction.

## Other coding considerations
Encapsulation would help restrict direct access to variables by making them private and protecting the modification of these internal states to only functions within the component script.

Object pooling would improve performance by reducing object instantiation and garbage collection by creating a set of reusable objects that can be activated and deactivated as needed.
