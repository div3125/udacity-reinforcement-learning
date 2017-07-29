# Train a Smartcab to Drive
Reinforcement Learning project for Udacity's Machine Learning Nanodegree

### Requirements
* Language:- **Python 2.7**

    Python libraries:
    - [NumPy](http://www.numpy.org/)
    - [pandas](http://pandas.pydata.org/)
    - [matplotlib](http://matplotlib.org/)
    - [Pygame](https://www.pygame.org/wiki/GettingStarted/) (optional)

    Additional software:
    
    * [Jupyter Notebook](http://ipython.org/notebook.html) to run IPython notebooks.

### Code
The original template and supporting files are taken from ```projects/smartcab``` folder of Udacity's  [machine-learning](https://github.com/udacity/machine-learning) repository on GitHub.

Review: [Smartcab rubric](https://review.udacity.com/#!/rubrics/106/view)

### Environment
The *smartcab* operates in an ideal, grid-like city (similar to New York City), with roads going in the North-South and East-West directions. Other vehicles will certainly be present on the road, but there will be no pedestrians to be concerned with. At each intersection there is a traffic light that either allows traffic in the North-South direction or the East-West direction. U.S. Right-of-Way rules apply: 
- On a green light, a left turn is permitted if there is no oncoming traffic making a right turn or coming straight through the intersection.
- On a red light, a right turn is permitted if no oncoming traffic is approaching from your left through the intersection.
To understand how to correctly yield to oncoming traffic when turning left, you may refer to [this official drivers' education video](https://www.youtube.com/watch?v=TW0Eq2Q-9Ac), or [this passionate exposition](https://www.youtube.com/watch?v=0EdkxI6NeuA).


### Run
In a terminal or command window, navigate to the folder `smartcab/` in project directory and run one of the following commands:

```bash
jupyter notebook smartcab.ipynb
```
or
```bash
ipython notebook smartcab.ipynb
```

This will open the Jupyter Notebook software and project file in your web browser.

To run the smartcab agent:-

`python smartcab/agent.py` or  
`python -m smartcab.agent`
