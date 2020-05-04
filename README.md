# Git and Python Set-up Verification
Students in BME 547 may use this repository as a test to make sure that they 
have successfully set-up their local git and Python.

1. Open up GitHub repository at <https://github.com/dward2/setup_verification>
2. Click on the green "Clone or download" button.
3. Make sure the pop-up box says "Clone with HTTPS."  If it doesn't, click on 
the "Use HTTPS" link so that it does.
4. Copy the URL from the pop-up box.  It should look something like:
`https://github.com/dward2/setup_verification.git`.
5. Open up a Git Bash, command window, or terminal window (will be called CLI,
command line interface, in further instructions).
6. Navigate, using the `cd` command, to a location where you would like to store
your repositories for this course.
7. Back on your CLI, type `git clone <URL>` where `<URL>` is the URL copied from
above.  Note, do not include the `<>`.  Hit return.
8. A new folder called `setup_verification` should have been created.  Move into
that directory by entering `cd setup_verification`.
9.  Test your ability to run Python by entering `python check_python.py`.  A
program should have run that printed out the Python version and saying that you
successfully ran Python.
10.  Test your ability to set up a virtual environment by entering 
`python -m venv myvenv`.  Next, enter `ls` to verify that a new folder called
`myvenv` was created.  
11. Activate the virtual environment by entering:  
  + **MAC/Linux**:  `source myvenv/bin/activate`
  + **Windows**: `source myvenv/Scripts/activate`  
  
12. Verify that the virtual environment activated by seeing `(myvenv)` in the
command line.
13.  Test your ability to add packages using `pip` by entering 
`pip install -r requirements.txt`.
14. To run one of the newly installed packages, enter 
`jupyter notebook jupyter_nb_check.ipynb`.  A Jupyter notebook should open
in a browser window.  Follow the brief instructions in the Jupyter notebook.
15. When finished, return to the CLI.  If you do not have access to a command
prompt, you may need to type `ctrl-C` to cancel the Jupyter notebook server
that is running.
16. Deactivate your virtual environment by entering `deactivate`.


