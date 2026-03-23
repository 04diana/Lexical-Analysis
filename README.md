# Lexical-Analysis

## Description
The language I chose is all combinations of 0,1,2 but it must not have 1101, 1122, 1011 or 1012.
An Automaton is a machine, either real or abstract, it runs by itself in other words it is a computational model that constructs an input by moving through a series of states or configurations.  An DFA is a deterministic finite Automaton that is considered deterministic if for every input, there is only one transition and therefore the machine is fully predictable. On the other hand, NFA is a nondeterministic finite Automaton where every state can have multiple possible next states for the same input


## Models


### NFA Diagram

<img width="751" height="421" alt="Automata drawio" src="https://github.com/user-attachments/assets/b5f5ae56-f95b-4b5f-b50f-a49fdb2e59c6" />




The NFA works by restricting all the sets that are prohibitted, those being 1101, 1122, 1011 or 1012 where each case would lead to a dead state and therefore reject those combinations. Going into Q5, is where the accepting states let there many combinations even so accepting strings with just one. 

### Regular Expression
The equivalent regular expression for this language is:

[regex here]

Explaination:

[explain how the regex represents the langauge]


## Implementation

### DFA Implementation

The DFA was implemented in Prolog (see automata.pl)

To run it:

swipl
["automata"].
run


### Regex Implementation 
The regex was implemented in Python (see regex.py)

To run it:

pythong regex.py

## Tests

### DFA Tests

the file 'test_automata.pl' contains the test cases

### Regex Tests 

The file 'test_regex.py' contains test cases

## Analysis


### Time Complexity

Both implementations have time complexity:

-DFA: O(n)
-Regex: O(n)

this is because....


### Comparison

DFA:
-
-
-

Regex:
-
-
-


## References

