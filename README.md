# PyCharm/GitHub Setup Check

## Problem Description
The purpose of this exercise is to be sure everything is set up correctly and to show you how to navigate GitHub and PyCharm. The code is provided for you - all you need to do is make one small edit.

* Open [src/mycode.py](src/my_code.py)
* Uncomment (remove the #) the print statement. Be sure there are no spaces between the margin and the print statement.
* Run the program by going to the Run menu and clicking Run. (There are 2 Run options in the menu. The first one will probably be greyed out - choose the second one.) You can also right-click on the code and choose Run.
  * If you have an error message, ask for help.

### Submitting to GitHub
* There are several steps to this. It takes practice, and will get easier to remember as you do it more often.
  * **Commit**  This command stores the changes you have made. You can think of it like taking a snapshot of your changes. They are saved but nothing else happens...yet. To commit, click the green ✔ in the toolbar at the top of the PyCharm window. Look for the prompt to type a commit message - this is where you will note the changes you made and the status of the project. For this assignment, something like `uncomment print - finished` is fine. Then click Commit.
  * **Push** This sends your commit ("snapshot") to GitHub and keeps it as the current working version of your project. Click the green arrow (points up and to the right) next to the commit button. Then click Push.
    * Note: There is also the option to Commit and Push at the same time. For now, I recommend doing them in 2 steps.
 
 ### Check GitHub
 * Go to your repo in GitHub and check to be sure it was updated in the last couple minutes.
 * Click the Pull Requests tab and then click on Feedback. Check your feedback - be sure it passed all tests and there are no style issues to be resolved. There are 3 types of tests used in this class: 
  * Classroom Workflow tests: these check to be sure your program functions correctly. 
  * Build and Test (pytest): these also check to be sure your program functions correctly. These tests require the use of functions so we'll get to these later.
  * Style tests: these check to be sure you are using good style (according to the [Python Style Guide](https://docs.python-guide.org/writing/style/)) There are two sytle checkers here: one is built into the "Build and Test" algorithm and the other uses a style-checking bot. Both show up under Feedback.  
   

### Submit confirmation on Canvas
* The last step is to submit a confirmation message on Canvas that you are done and the tests have passed.

### This will get easier!😊🦉


**Attribution:**

Thank you to Bianca Ruiz [@RuiztheRuler](https://github.com/RuizTheRuler) for providing a great starting place for automating feedback!