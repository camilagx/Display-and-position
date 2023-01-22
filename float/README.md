# Floats
![image](https://user-images.githubusercontent.com/99628526/213896537-75d3f74b-acae-48a7-9fbc-79b0f9a9ea07.png)

### Using Clear Property
**Clear** property specifies what should happen with the element next to a floating element.

clear: none | left | right | both | initial | inherit;

left: The element is pushed below left floated elements

initial: sets this property to its default value

inherit: inherits this propery from its parent
**Resource:** MDN

#### Notes

- If you float elements to the right, it inverts the order of the elements.

#### Best Practice

1. Have a container for floated items
This makes it easier to use the clear property to avoid floating other elements
