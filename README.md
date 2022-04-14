# Assignment-2
Part 1:
Based on what we know about linked lists, stacks, and queues, design a queue data structure:
I am going to use a line of parked carswaiting at a traphic light to leave. There will be two roadsleading to this that are queue 1 and 2 that will fill in the 
spots as car leaves.

What functions are we likely to need for a queue to function like the one discussed in class?
We will need a function to turn the green light on and have a car Dequeue when wanted. 
A function to have a car from one of the queue fill in the open spot. 

What values will we need to know about the structure for our queue to function properly?
We will want to know how spots are avaliable.
What decides when the light turns green. 
Which queue fills in the empty spot. 


Part 2:
Based on what we know about linked lists, design a list data structure that allows us to add (insert) or remove (delete) values at a given location in the list (instead of the top of a stack or the front or back of a queue):
I am going to use a parking lot for an example. 

What functions are we likely to need for a list to function like this?
A function to decide how many spots are avaliable.
Something that chooses which parking spot number is chosen for the car to leave.
Function to tell a new car to park when a spot is avaliable.

What values will we need to know about the structure for our list to function properly?
We will need to know the values of the parking spots.
How many spots are avlible and need to be filled at one time. Can spots be empty?
How many cars can be pulled from the line to fill the spots at once.
