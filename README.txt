Project Title:

Text Editor 

Problem Statement:

Given a text Editor developed by Engineers at QwickType Software which didn't met the requirements to reduce the time in copying and pasting there by reducing the speed of their development workflow. Task is to improve the given Text Editor by reimplementing or extending it with a focus on performance.

High level Approach:

Before stating my approach, I would like to I discusses about the current version which performs string manipulation which are in general immutable that is cannot be changed. This causes excess time usage while performing operations like cut and paste. These operations also lead to memory wastage causing increasing runtime. 

Thus, in this approach of mine I have implemented Linked List data structure which is dynamic and can be easily grown and shrunk while execution by simply allocating and deallocating memory. It also has better performance while performing operations like insertion and deletion thereby reducing the runtime, but memory usage increases as east character of string is stored as an object in linked list. So this can be considered as an trade-off for the purpose of speed. 

Other approach could be to use tree data structure which increases the speed drastically to be more specific a tire data structure can be used to store. But trade-off with this approach is it makes the code too complex would have tried it if I had more time for the project. 

Procedure to run the program:

1. Change the address path to the dfault.dic path according to the system.

2. Run the python program using:
			python editor.py
You can see the results in the command prompt. 


Performance Evaluations: 

Default Benchmark Performance Results

Evaluating case: "Hello friend"
100 cut paste operations took 0.0001124 s
100 copy paste operations took 8.09e-05 s
100 text retrieval operations took 1.25e-05 s
100 mispelling operations took 0.0093297 s


Improved Benchmark Performance Results

Evaluating case: Hello friends
100 cut paste operations took 0.0011671 s
100 copy paste operations took 0.004736 s
100 text retrieval operations took 0.0010046 s
100 mispelling operations took 0.0011393 s

