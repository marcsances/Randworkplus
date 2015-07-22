# Randworkplus
============
Intepreter of Randwork+, a nondeterministic programming language [featured on Esolang, the esoteric programming languages wiki](http://esolangs.org/wiki/Randwork).

Write your program, save it as a text file and run ```./randworkplus <program>```.

Randwork+ is a joke language. The specification is not strict, so I made several...

## Assumptions
============
* Instructions do not span over multiple lines.
* Instructions can be chained, e.g. ```If you want If you want Jump to a line``` jumps to a randomly chosen line with 25% probability.
* The ```Do whatever you want``` instruction is just ```Do anything``` executed random number of times between 0 and 255.
