- it seperates the common reusable object with no state change and reuses it without creating new memory so that the load on ram is reduced.
- Flyweight is a structural design pattern that lets you fit more objects into the available amount of RAM by sharing common parts of state between multiple objects instead of keeping all of the data in each object.
- Intrinsic Object is the one which will not have the state changed
- Extrinsic object is the one where the state will change
- Intrinsic state refers to the state that belongs to the flyweight object. The intrinsic state is immutable. E.g.: color and height.
- Extrinsic state varies for each object and is stored outside the object. The extrinsic state is mutable. E.g., position