# How to Complete and Submit Homework

1) Go to your repository and click the "CODE" button.  This will give you options to code locally (aka download the entire repository onto your computer and make edits on your computer) or to code through GitHub Codespaces.  **NOTE:** Repository is a codebase that can be thought of as the "official" version of all the code in a project.

![repo_landing](/assets/01_repo_landing.png)

2) Click on the "Create codespace on main" button.  If you already have a codespace created, just click on the codespace name to use it.

![repo_code](/assets/02_repo_code.png)

3) After it loads up (it may take a minute or two) you will see the default interactive development environment (IDE).  On the left are buttons for looking at files, search, version control, debugging, IDE extensions, and GitHub.  As highlighted, we are viewing the files.  Click on the `homework_1.ipynb` file.  The filename extension `ipynb` means an iPython notebook.  I personally find iPython notebooks are one of the best ways for students to learn coding.  Notebooks are also heavily used when we work on coding for data science, data analytics, machine learning, and artificial intelligence.

![code_space_landing](/assets/03_code_space_landing.png)

4) When we first start coding a notebook, the IDE will ask us to if we want to install the Python extension.  Since we want the IDE to give us hints we should click the "Install" button.

![hw_landing](/assets/04_homework_landing.png)

5) After the installation is complete (you can tell when it gives you an option to uninstall the extension, don't uninstall) close out the extension tab up top and the terminal below.  We won't need these windows.

![ext_install](/assets/05_ext_install.png)

6) Also, the first time using a notebook we need to choose a Python environment (the interpreter version of Python and any extra packages we might want to include).  Click on the "Select Kernel" button.  **NOTE:** A package is code that someone else (or maybe you in the past) has written that we can use in our code.  Remember, coding is about being lazy.  Don't spend time building something someone has already built just use what they built.

![kernel_1](/assets/06_choose_kernel.png)

7) Click on the "Install/Enable suggested extensions" option.  This will take a few seconds to install the packages to a Python environment we will be using.

![kernel_2](/assets/07_choose_kernel_2.png)

8) Once the packages have been installed we can finally choose the kernel (aka the Python environment we just created).  Click on "Python Environments".

![kernel_3](/assets/08_choose_kernel_3.png)

9) Now click on the "Recommended" option as that is the environment we just created.

![kernel_4](/assets/09_choose_kernel_4.png)

10) You can now see that the "Select Kernel" button on the top right has been replaced by the Python environment we selected.  Now we are ready to code.  In iPython notebooks the code is run cell-by-cell, meaning you do not run all the code in the notebook at once.  Let's click on the first cell.

![hw_start](/assets/10_homework_start.png)

11) We will first import (aka load a package) into the notebook.  We are importing the `datetime` package in this homework.  Let's run the cell to import the package.  We can do this by either clicking the "play" button to the left of the cell or by pressing "shift-enter" together.

![cell_1](/assets/11_run_cells.png)

12) To the left of the cell there is a box that indicates if the cell has been run (if it has there will be a number indicating the order it has been run within the notebook), also a check if the code has been successful (or and "X" if it failed).  Let's move on to the next cell (by clicking on it), fill in values for the variables, and running the cell as described above.

![cell_2](/assets/12_run_cells_2.png)

13) After you have completed the homework (filled in all the cells that need filling in) complete the following.  On the left menu we can see the item with 3 circles and some lines connecting them.  That is version control.  The number in the blue circle is number of files that have been modified.  Click on that icon.

![cell_3](/assets/13_run_cells_3.png)

14) Version control is how programmers "merge" their work onto a project.  This allows many people to work on the same project without having to manually share updated files with everyone else.  We can see under "Changes" all the files that have been updated.  The "M" on the right of the file means it has been modified.  To add this file so that everyone receive the changes click on the "+" button.  This will "stage" the file.

![version_ctl](/assets/14_select_version_ctl.png)

15) As we can see, the homework file is now under "Staged Changes".  This means we are telling version control that the staged file will be committed.  Committing a file means it will be updated in the repository.  But before we commit we need to add a message.  Usually we add an informative message like "homework 1 completed".  **NOTE:** This is something you must do or else a commit will fail.

![added_changes](/assets/15_add_changes.png)

16) Now that we have added a message, we can finally commit the files to the repository.  Click on the "Commit" button.

![added_message](/assets/16_add_message.png)

17) To complete the process we need to sync the changes.  Click on the "Sync Changes" button.

![committed](/assets/17_commited.png)

18) A popup box will show up asking you if you are completely sure to merge your changes onto the repository.  Click on the "OK" button.

![synced](/assets/18_sync_message.png)

19) We are done.  On the bottom right there is a popup box asking you if you want GitHub codespaces to regularly sync your files.  You can ignore that by clicking "No" or closing the box.  You are now done submitting your homework!

![done](/assets/19_done.png)