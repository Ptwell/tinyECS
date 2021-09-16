CPSC 427 2021 Fall
Name: Peter Le
Student #: 21320163

	For SoA, struct of arrays, the struct is a struct of two ComponentContainers (one for velocity and one for position respectively). 
	The ComponentContainers of the struct takes on the role of the 'array,' in which one is for velocity and a different one is for position. 

	For AoS, array of structs, the struct is a struct of two values (one for velocity and one for position respectively). 
	The ComponentContainer takes in the component type of this struct and acts as an array.

	In the component section, since the array of structs made the struct contain both position and velocity, the component becomes singular. 
	This results in the animals that adopted the AoS having a component called motion with two values/'aspects' instead of the two components velocity and position. 

