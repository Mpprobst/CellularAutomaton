CS 450
Assignment3: Smalltalk
BY: Michael Probst
LAST MODIFIED: 25 March 2019 at 18:57 EST

PROGRAM FILE: a3.st.txt


+++++++++++++++++++++++++++++++++++
+           HOW TO RUN            +
+++++++++++++++++++++++++++++++++++


To run this program, ensure you have gst installed, then simply type "make run" into your terminal.

+++++++++++++++++++++++++++++++++++
+               INFO              +
+++++++++++++++++++++++++++++++++++

This program simulates a cellular automaton containing a circular array of 52 playing cards initialized with 13 of each suit: Club, Diamond, Heart, and Spade (noted by C, D,H, and S, respectively in the simulation). At each time step, each card will look at its immediate neighbors and if the original card has a black-colored suit, its value will become the product of the value of its neighbors', however if the card is red, its new value will be the sum of its neighbor's values. The deck will start in lexicographical order (Suit taking precedence over value) and will step in time 20 times after initialization. This program is written in GNU smalltalk.

