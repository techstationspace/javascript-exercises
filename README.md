These are a series of javascript exercises intended to be used alongside the curriculum at 'The Odin Project'  They start very simply, but get more involved as you progress through them.

There will eventually be a suggested order of completion, but at this time since we are still in the process of creating more exercises the order is subject to change and has not yet been specified... In general however there are a couple which make a good "starting point" feel free to at least start with these:

1. Hello World
1. Repeat String
1. Reverse String

## HOW TO USE THESE EXERCISES
Before you start you should have a few things installed on your machine:
1. NPM.  To check if you have NPM, type `npm --version` in a terminal. If you get back `Command 'npm' not found, but can be installed with:`, do NOT follow the instructions in the terminal to install with `apt-get` (this causes permission issues). Instead, install NPM/Node with NVM by following the instructions [here](https://github.com/TheOdinProject/curriculum/blob/master/web_development_101/installations/installing_node.md).
3. Clone this repo.
4. Jest.  Jest is a testing framework for Javascript. You need to install it with `npm install`.  Type `npm run jest -- -v` to check for it.

Each exercise includes 3 files, a markdown file with a description of the task, an empty (or mostly empty) javascript file, and a set of tests.  To run the test for a specific exercise open the terminal and run `npm run jest -- myExercise/filename.spec.js`. For example, to run the helloWorld test: `npm run jest -- helloWorld/helloWorld.spec.js`. This should find and run the test file and show you the output.  Upon first running the tests you will find that the tests fail: this is by design!  Your task is to open up the javascript file and write the code needed to get all of the tests to pass. Some of the exercises have test conditions defined in the spec file that are defined as 'xit' compared to 'it'. 

NOTE: This is purposeful, and as you test your solution against the first 'it', on success you will change the next 'xit' to an 'it' and test your code again, until all conditions are satisfied.

The first exercise, `helloWorld` will walk you through the process in more depth.


## a quick note!

The generator exercise is not actually an exercise… it is a script that generates exercises. I was using it when I wrote them so I didn’t have to hack out the same boilerplate code every time I wrote a new one.
