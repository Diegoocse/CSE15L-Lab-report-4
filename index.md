Log into ieng6:

<img width="826" alt="Screenshot 2024-06-05 at 6 52 28 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-4/assets/146890166/913c7e34-47f0-4936-b52c-86c60ab0a008">



   
2) This command initiates an SSH connection to the ieng6 server using your ieng6 username, allowing you to access the server remotely.




Clone your fork of the repository from your Github account (using the SSH URL):


<img width="747" alt="Screenshot 2024-06-05 at 6 58 44 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-4/assets/146890166/39cde5cc-ab2b-410c-afb7-f32f7d13ecbe">

2) de
3) Clones the forked repository from your GitHub account to your local machine, providing you with a local copy of the repository to work with.

Run the tests, demonstrating that they fail:

<img width="1094" alt="Screenshot 2024-06-05 at 7 58 50 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-4/assets/146890166/1cccb726-f38c-4bdf-be62-e067fcd41c5d">


2)  de
3)  Changes the directory to the repository directory and runs the tests. The tests fail, indicating that there are issues in the code that need to be addressed.

Edit the code file to fix the failing test:

1)
<img width="657" alt="Screenshot 2024-06-05 at 8 36 49 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-4/assets/146890166/0a10cd1b-1067-49c8-a578-e7b675ff8872">

2) the commands that
   
3) The command opens the Example.java file in the src directory for editing in the vim text editor.



Run the tests, demonstrating that they now succeed:

1)
<img width="1014" alt="Screenshot 2024-06-05 at 8 05 12 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-4/assets/146890166/4f3df4df-ceb7-4de8-8ecf-136203a9ca8a">

2)deknd

3)The command runs the run_tests.sh script, which executes the tests again after you made changes to the code in Example.java. This is to demonstrate that the failing test(s) have been fixed and the tests now pass successfully.



Commit and push the resulting change to your Github account (you can pick any commit message!):

1)
<img width="617" alt="Screenshot 2024-06-05 at 8 22 31 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-4/assets/146890166/085853e9-aac9-4dde-9aca-053cd2573131">

2) dedk

3) git add .: Stages all modified files for the commit.
git commit -m "Fixed methods": Commits the changes with the specified commit message.
git push origin main: Pushes the committed changes to the main branch of your GitHub repository.


