

# Homework Guidelines

## 1. Philosophy

:writing_hand: This is a _hands on_ course, meaning coding homework and projects are a key part of the learning. You are expected to spend at least as long solving problems as attending live classes. However, homeworks 1-5 test variations of what was already covered in class, and whilst challenging, are not meant to be extremely difficult. So if you are stuck, please consider revisiting one of the previous course notebooks.


:handshake: This is also a _micro-class_, where collaboration is encouraged, and guidance is expected. Do talk to your fellow students about certain problems, and plan coding sessions. Do ask for teachers' help in the discord, and look for answers online. However, whereas collaboration and guidance improve learning, plagiarism does not. So please don't copy-paste answers without understanding them, and don't ask for assistance without attempting the problems yourself.

:partying_face: Most important of all, homework is purposefully sometimes frustrating and sometimes rewarding, so have fun!


## 2. Format

For each homework, you will be given a jupyter notebook that you are expected to **fill in** and **submit**. The notebooks will contain three types of cells:  

* instructions and background information in the form of text cells
* working code cells to set up the exercises
* empty or partial code cells you are expected to complete 

The latter will always be clearly marked with `# INSERT YOUR CODE HERE` comments. You are also encouraged to add new code or text cells, or anything that accomplishes the tasks and/or answers the questions. 

## 3. Submission

Please upload the completed jupyter notebook file (`.ipynb`) in this [airtable](https://airtable.com/shri5saP3xxEDtrHQ).

## 4. Grading Scheme


Each problem has a three-tier grading scheme.

For :brain: **:written questions**, :star_struck: will be given for a comprehensive answer, :slightly_smiling_face: for a partial answer, and :confused: for a wrong answer.  

For :muscle: **coding tasks**, :star_struck: will be given to functional and quality code, :slightly_smiling_face: for partially functional or convoluted code, and :confused: for wrong approaches. Code quality includes using the correct methods, following api "best practices", efficiency, clarity, and comments. This does means that you may get :slightly_smiling_face: for broken code if the attempt is coherent, and commented or self-explanatory, so always include your best attempt!

Where applicable, **unit tests** will be provided underneath the incomplete code cells to help you validate your work. **Warning: The unit tests are not used for grading**. The behaviour of your code will be manually assessed. Code that passes a unit test is not necessarily accomplishing the task correctly, so please check and debug your code thoroughly. However , failing the unit tests is a strong indication that you should fix your code, and passing the unit tests is a good sign that your code is working as expected.

**Bonus** tasks and questions serve are not mandatory. Complete them if you wish to take your learning further, or if you find the problems fun!

## 5. Late Submissions

### Homeworks 1-5

Homeworks are given on Wednesdays, and you have 5 days to complete them. i.e the deadline is on **the next Monday lecture**. Please respect deadlines - it is important to assimilate the content through practice and validate your learning before the next week. 

### Final Project

The final project will start on the 28.06.2021, and you will be given 1 week to complete it.

## 6. Tips

#### Methodology

Approach the problems through _exploration_. You can `print()` your variables throughout the exercise to check your progress. Remember to check the relevant documentation!

#### Final check

When graded, the notebooks will be run cell by cell from top to bottom. Therefore it's a good idea to do a "final check" before submission, by [restarting the kernel](#Restarting-the-kernel) and running all cells in order. All unit tests should pass! 

#### Restarting the kernel

Jupyter notebooks share variables between cells. This means that outputs are dependent on the _order_ in which the cells were executed. Keep this in mind if you ever backtrack during your assigment, a unit test might be failing solely because of code run _after_ the cell in question! If in doubt, you can restart the [kernel](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#kernel) by selecting `Kernel>Restart` in the notebook menu. This will clear all state in the notebook (but keep cell contents), and start fresh.

#### Saving your work

When programming, it is very easy to lose a change, or to accidentally break working code. Whilst jupyter notebooks support basic "undo" features, you might want to backup your homeworks as you complete them. You can do this by simply copying the notebook with `File>Make a Copy...` in the menu. If you are comfortable with [git](https://git-scm.com/), you can also create a new branch, and commit your changes there. Careful if you commit to the master branch, you might have conflicts next time you pull the repository.


#### Jupyter Notebook Tutorial

If you need a refresher on jupyter notebooks, check out this [tutorial notebook](https://mybinder.org/v2/gh/ipython/ipython-in-depth/master?filepath=binder/Index.ipynb), or the [documentation](https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Notebook%20Basics.html).
