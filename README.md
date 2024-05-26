# Project-3-Logic-and-Classic-Planning-in-Pacman
In this project, you will use/write simple Python functions that generate logical sentences describing Pacman physics, aka pacphysics. Then you will use a SAT solver, pycosat, to solve the logical inference tasks associated with planning (generating action sequences to reach goal locations and eat all the dots),
localization (finding oneself in a map, given a local sensor model), mapping (building the map from scratch), and SLAM (simultaneous localization and mapping).

As in previous programming assignments, this assignment includes an autograder for you to grade your answers on your machine. This can be run with the command: `python autograder.py`.

See the autograder tutorial in Project 0 for more information about using the autograder.

The code for this project consists of several Python files, some of which you will need to read and understand in order to complete the assignment, and some of which you can ignore. You can download all the code and supporting files as a zip archive.

| Files you will edit       |                                           |
|---------------------------|-------------------------------------------|
| `logicPlan.py`            | Where you will put your code for the various logical agents. |

| Files you might want to look at       |                                           |
|---------------------------------------|-------------------------------------------|
| `logic.py`                            | Propositional logic code originally from [AIMA-Python](https://code.google.com/p/aima-python/) with modifications for our project. There are several useful utility functions for working with logic in here. |
| `logicAgents.py`                      | The file that defines in logical planning form the two specific problems that Pacman will encounter in this project. |
| `pycosat_test.py`                     | Quick test main function that checks that the pycosat module is installed correctly. |
| `game.py`                             | The internal simulator code for the Pacman world. The only thing you might want to look at in here is the Grid class. |
| `test_cases/`                         | Directory containing the test cases for each question |

| Files you will not edit               |                                           |
|---------------------------------------|-------------------------------------------|
| `pacman.py`                           | The main file that runs Pacman games.     |
| `logic_util.py`                       | Utility functions for logic.py            |
| `util.py`                             | Utility functions primarily for other projects. |
| `logic_planTestClasses.py`            | Project specific autograding test classes |
| `graphicsDisplay.py`                  | Graphics for Pacman                       |
| `graphicsUtils.py`                    | Support for Pacman graphics               |
| `textDisplay.py`                      | ASCII graphics for Pacman                 |
| `ghostAgents.py`                      | Agents to control ghosts                  |
| `keyboardAgents.py`                   | Keyboard interfaces to control Pacman     |
| `layout.py`                           | Code for reading layout files and storing their contents |
| `autograder.py`                       | Project autograder                        |
| `testParser.py`                       | Parses autograder test and solution files |
| `testClasses.py`                      | General autograding test classes          |

**Files to Edit and Submit:** You will fill in portions of logicPlan.py during the assignment. You should submit these files with your code and comments. Please do not change the other files in this distribution or submit any of our original files other than these files.

**Evaluation:** Your code will be autograded for technical correctness. Please do not change the names of any provided functions or classes within the code, or you will wreak havoc on the autograder. However, the correctness of your implementation -- not the autograder's judgements -- will be the final judge of your score. If
necessary, we will review and grade assignments individually to ensure that you receive due credit for your work.
