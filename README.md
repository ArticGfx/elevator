
This project represents an elevator of a 4 floors building.
this elevator has as his core feature the ability to understand the closest "calling floor" even if the closest flor calls the elevator after the "processing floor". 
EX: the elevator is moving from 1 to 4
floor 3 make a call while the elevator is at floor 2 so the new sequence of stop id 1->3->4 rather than 1->4->3.
This process is realized by ordering every single call in 2 register file, one from the call inside the elevator and one for the call outside the elevator and the analysing in this order 1->2->3->2->1 every floor and if there's a value saved in the register indicating tha floor then the elevator move to that floor.
Here's a quick image of the final project.
