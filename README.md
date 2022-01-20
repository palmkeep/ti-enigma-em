
# Enigma simulator implemented in TI-Basic #

Written in 2015 during high school.

From what I can remember this implementation does not line up perfectly with others I could find online at the time.
Additionaly it lacks the plugboard from the front panel.

The idea was to write an interpreter and check correctness on something with a proper keyboard.


## Program control flow ##

Started by running SIMENIGMA which loops endlessly prompting for a character at a time stored in S.

Rotors are simple (messy) if-else statements that modify S and offsets are handled per-position separately from the rotors.
