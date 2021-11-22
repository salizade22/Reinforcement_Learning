# Reinforcement_Learning
![alt text](https://github.com/salizade22/Reinforcement_Learning/blob/main/source/Screenshot%202021-11-22%20at%2016-15-13%20Project%203%20Reinforcement%20Learning.png)
=======================================================================================================================================================================

Introduction
=============
In this project, you will implement value iteration and Q-learning. You will test your agents first on Gridworld (from class),
then apply them to a simulated robot controller (Crawler) and Pacman.
As in previous projects, this project includes an autograder for you to grade your solutions on your machine. This can be run on all questions with the command:

```
python autograder.py
```

It can be run for one particular question, such as q2, by:

```
python autograder.py -q q2
```

It can be run for one particular test by commands of the form:
```
python autograder.py -t test_cases/q2/1-bridge-grid
```

| Files to edit        |                                 |
|-----------------|------------------------------------------------|
| ``` valueIterationAgents.py ```           | A value iteration agent for solving known MDPs.                            |
| ``` qlearningAgents.py ```        | Q-learning agents for Gridworld, Crawler and Pacman.                                     |
| ``` analysis.py ``` |  file to put your answers to questions given in the project                                 |
| --------------------           | ----------                               |
| Other files |          |
|``` mdp.py ```           | Defines methods on general MDPs.                            |
| ``` learningAgents.py ```        | fines the base classes ValueEstimationAgent and QLearningAgent, which your agents will extend.                                     |
| ``` util.py ``` |  Utilities, including util.Counter, which is particularly useful for Q-learners.                                |
| ``` gridworld.py ```| The Gridworld implementation. |
| ``` featureExtractors.py  ``` | Classes for extracting features on (state,action) pairs. Used for the approximate Q-learning agent (in qlearningAgents.py). |
| environment.py              | Abstract class for general reinforcement learning environments. Used by `gridworld.py`. |
| --------------------------- | --------------------------------------------------------------------------------------- |
| ``` graphicsGridworldDisplay.py ```| Gridworld graphical display.                                                            |
|``` graphicsUtils.py         ```   | Graphics utilities.                                                                     |
|``` textGridworldDisplay.py  ```   | Plug-in for the Gridworld text interface.                                               |
|``` crawler.py               ```   | The crawler code and test harness. You will run this but not edit it.                   |
|``` graphicsCrawlerDisplay.py ```  | GUI for the crawler robot.                                                              |
|``` autograder.py             ```  | Project autograder                                                                      |
|``` testParser.py             ```  | Parses autograder test and solution files                                               |
|``` testClasses.py            ```  | General autograding test classes                                                        |
|``` test_cases/              ```   | Directory containing the test cases for each question                                   |
|``` reinforcementTestClasses.py ```| Project 3 specific autograding test classes                                             |






       
