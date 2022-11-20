# Test First Thinking

When you're not used to Test Driven Development and you start working on a new problem, a common pitfall is to immediately jump into the solution space and think about algorithms and data structures.
You would then think: "How would my implementation code look like? I could do a loop!".
The thinking might even lead to writing implementation code inside the test-case.
This is not a healthy way to start when doing TDD.
Jumping to solutions quickly causes bias and leads to results that are needlessly complicated.
In TDD it is healthy to take a step back and ignore implementation details until they become more obvious and evident.
Taking a step back can be hard.

## Learning Objectives

- Thinking in terms of test-code rather than production-code when tackling a problem.
- Being able to write a first test case for systems that are "pure" as in "pure function" thus have an input and an output and no side-effects.

## Session Outline

- 5 min connect: Test After: Testing an already written Code
- 5 min connect: Teamreview
- 10 min concept: Questions that help focus on the problem rather than the solution
- 25 min concrete practice: Leap Years
- 5 min conclusion: Explain in own Words

### Connect - Test After
Recall existing testing skills by writing a test for a code that already exists.
Show the pseudocode of a function called `add` that adds two numbers and returns the result.
Ask the participants to get into small groups and write a simple test case for that function in pseudo code.
Make it clear that the test is supposed to be pseudo code and it doesn't have to compile.
The goal is to have the test contain everything a typical test-case does.

### Connect - Teamreview
Review at least one of the pseudocode-tests together with all participants. 
Make them question the test. 
"Does it have everything a test should have?"
"Does it have an assert?" 
"Does it have an action?"
AAA is not the focus of this exercise, but it is necessary that the participants understand what a test case looks like.

### Concept - Questions that help focus on the problem rather than the solution
Lay out the helping Questions, and use them on a simple problem such as Arabic Numbers to Roman Numerals conversion

- **What is the name of the thing that we want to build?** 
	- Gives it a Name!
- **What are its inputs and what are its outputs?**
	- Defines the API through arguments and a return value.
- **What is an example how it would be used?**
	- Now we get into defining a scenario.
- **What is the simplest possible example you can think of, that would still add value to the user?
	- Now we're getting to a good starting point.

### Concrete Practice - Leap Years
Instruct the participants to form the same groups and use those 4 Questions on the Leap Years Kata.
The Goal is to come up with a good first Test case. Bonus is, if it compiles and fails.

### Conclusion
Have the participants explain in their own words what they think they need to focus on when starting Test-First.
