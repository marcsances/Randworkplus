# Randworksharp

Intepreter of Randwork#, a nondeterministic programming language [featured on Esolang, the esoteric programming languages wiki](http://esolangs.org/wiki/Randwork).

Write your program, save it as a text file and run ```./randworksharp <program>```.

Randwork# is a joke language. The specification is not strict, so I made several...

Randwork# is a simple 1 line variation of Randwork+ interpreter, which instead of spamming Hello World messages dumps all variables. Enjoy I guess. The original Randwork+ interpreter is available [here](https://github.com/giargiano/Randworkplus).

All credit goes to him.

## Assumptions
* Instructions do not span over multiple lines.
* Instructions can be chained, e.g. ```If you want If you want Jump to a line``` jumps to a randomly chosen line with 25% probability.
* The ```Do whatever you want``` instruction is just ```Do anything``` executed random number of times between 0 and 255.