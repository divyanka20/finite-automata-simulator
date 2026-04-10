Finite Automata Simulator

Features:
1.	Build automata visually: add/edit/delete states and transitions
2.	Supports DFA (strict one transition per symbol) and NFA (multiple transitions + ε)
3.	Step-by-step or auto-play simulation with adjustable speed
4.	Live ε-closure computation and active state tracking for NFA
5.	Color-coded graph: start state, accepting states, and current state highlighted
6.	Full transition trace log for every simulation run
7.	Export/import automata as JSON (canvas positions preserved)
8.	Four built-in examples to get started instantly

Usage:

Building an automaton
1.	Double-click the canvas to add a state, or use the Add State button in the left panel
2.	Set one state as the start state and one or more as accepting states
3.	Use the Add Transition form to connect states with symbols
4.	Switch between DFA and NFA mode using the toggle in the header

Running a simulation
1.	Type an input string in the Simulation panel
2.	Click Run to initialise
3.	Use Step to advance one symbol at a time, or Play to run automatically
4.	Watch the current state highlight on the graph and the trace log fill in
5.	The result (ACCEPTED or REJECTED) is shown when the string is fully consumed

Importing and exporting
•	Click Export to download the current automaton as a .json file
•	Click Import to load a previously saved automaton

Tech Stack:
•	Graph rendering: D3.js v7
•	Logic & UI: Vanilla JS, HTML, CSS
	
