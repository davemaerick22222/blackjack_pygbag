Setting Up
----
First, make sure you have Python 3.\* and the latest pip >= 20.\* (Check the `Notes & FAQ` section below if you're having trouble with this). Then, here is the preferred way to set up (if you have another way, feel free to do it):

1. Install [anaconda](https://docs.anaconda.com/anaconda/install/) to set up a virtual environment
2. `conda create -n cse150b python=3.10`
3. `conda activate cse150b`
4. To install PyGame, `pip install pygame`. We will use PyGame for all assignments in this class.

You can run `conda deactivate` to deactivate the environment. The next time you want to work on the assignment, type `conda activate cse150b` first to use the exact same environment with PyGame installed.


Usage
----
Simply run `python main.py` and you will see the grid world window. By pressing `enter` you see how DFS finds a path (given DFS is buggy, as you will see). Pressing 2, 3, or 4 should respectively run BFS, UCS, A\* in a similar way, which you will implement (since right now it does nothing).
