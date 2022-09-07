# Project Idea: Rubix Cube Solver

# Jack Arndt

One of my favorite hobbies for a lot of my life has been learning and solving various kinds of rubix cubes. The classic, of course, is the 3x3x3, and though I attempted to learn speedsolving at one point, there are a huge amount of algorithms to remember. However, a lot of these methods to solving in a very low number of moves exist online, and it wouldn't be too hard to create a program which, given an input, decides the most efficient movesets to get to the next step of solving. It would take a tremendous amount of processing to solve the entire thing from start to finish recursively, but it would be possible to solve it in steps recursively, like doing the first cross or first two layers before moving on to the next steps. A computer can also easily keep track of all of the colors based on every moveset, so all it needs is the initial state of the cube.

This can be accomplished with a C++ program which takes every color on every face as an input (based on a specified orientation), then prints out the entire moveset required to solve the cube.

This could be sold as an app by people who have the classic toy sitting on their shelf collecting dust, all mixed up, and want to be wowed by a cool program which solves it for them
