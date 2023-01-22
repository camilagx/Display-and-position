# Floats

##### Notes

- If you float elements to the right, it inverts the order of the elements

### Using Clear Property
**Clear** property specifies what should happen with the element next to a floating element.

clear: none | left | right | both | initial | inherit;

left: The element is pushed below left floated elements

initial: sets this property to its default value

inherit: inherits this propery from its parent
**Resource:** MDN
###### Best Practice

1. Have a container for floated items
This makes it easier to use the clear property to avoid floating other elements