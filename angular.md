##### Property binding
- When binding to a style using ``` [style.{style prop}] ```, the computed value should not contain any semicolon at the end of the value (if it is a string)

##### Property getters and setters in interfaces
To tell that a class which implements an interface should only have a property *getter*, the property should be defined as **readonly** in the interface. To allow the *setter* too, it is enough to specify the property without any modifier. *Getters* and *setters* in a class which implements an interface can be overridden by subclasses.

##### Reference to directives in components
To get the reference to any directive associated to a component, *inject* it into the component's constructor.

##### Component styling
To apply a style to the html component element itself the **:host** selector can be used to target it.