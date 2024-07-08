# Clean architecture
1. Clean architecture is blueprint for a modular system which strictly follow the design principle called seperation of concerns.
2. This style of architecture focuses on diving software into layers to simplify the development and maintenance of the system itself.
3. When layers are well separated individual pieces can be reused as well as developed and updated independently.
4. Clean architecture is one of the most powerful solutions to build clean apps with independent data layers that multiple teams can work on the resulting app would also be scalable readable testable and can be easily maintained at any time.

* DATA LAYER
   * repositories
   * data source (remote, local)
   * models
   
* DOMAIN LAYER
   * entities
   * repository interfaces (Abstract classes, contracts)
   * use cases (Signup, login)

* PRESENTATION LAYER
   * pages
   * state management (provider, bloc)
   * widgets

Entities:-
  Entities are business objects of an application or a system