Log into ieng6:

<img width="826" alt="Screenshot 2024-06-05 at 6 52 28 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-4/assets/146890166/913c7e34-47f0-4936-b52c-86c60ab0a008">

2) Keys pressed: ssh `<space>` dortegarobles@ieng6.ucsd.edu `<enter>`

   
3) This command initiates an SSH connection to the ieng6 server using my ieng6 username, allows me access to remote server.




Clone your fork of the repository from your Github account (using the SSH URL):


<img width="747" alt="Screenshot 2024-06-05 at 6 58 44 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-4/assets/146890166/39cde5cc-ab2b-410c-afb7-f32f7d13ecbe">

2) Keys pressed: git`<space>`clone `<space>` git@github.com:Diegoocse/lab7.git`<enter>`
   
3) Clones the forked repository from my GitHub account to my local machine, provides me with a local copy of the repository to work with.

Run the tests, demonstrating that they fail:

<img width="1094" alt="Screenshot 2024-06-05 at 7 58 50 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-4/assets/146890166/1cccb726-f38c-4bdf-be62-e067fcd41c5d">

2) Keys pressed: `<up>``<up>``<enter>`,javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
was 2 up in the search history, so I used up arrow to access it. To execute  java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests
So that the test could run I pressed, `<up>``<up>``<up>``<enter>`

   
3)  compiles and runs the tests. The tests fail, indicating that there are issues in the code that need to be addressed.

Edit the code file to fix the failing test:

<img width="657" alt="Screenshot 2024-06-05 at 8 36 49 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-4/assets/146890166/0a10cd1b-1067-49c8-a578-e7b675ff8872">

2)Keys pressed were `<j>`so I could move down until I got to the bug section of the code. I pressed `<l>` to get to index1 and hovered over 1 pressed `<x>` then I pressed `<I>` and corrected 1 to 2 then I pressed `<esc>` to finish
   
3) These commands edit the file in the vim text editor.


Run the tests, demonstrating that they now succeed:

<img width="1014" alt="Screenshot 2024-06-05 at 8 05 12 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-4/assets/146890166/4f3df4df-ceb7-4de8-8ecf-136203a9ca8a">

2)Keys pressed: `<up>``<up>``<up>``<enter>`,javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
was 2 up in the search history, so I used up arrow to access it. To execute  java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests
So that the test could run I pressed, `<up>``<up>``<up>``<up>``<enter>`


3)compiles and runs previous failing tests. This is to demonstrate that the failing tests have been fixed and the tests now pass successfully.



Commit and push the resulting change to your Github account (you can pick any commit message!):

<img width="617" alt="Screenshot 2024-06-05 at 8 22 31 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-4/assets/146890166/085853e9-aac9-4dde-9aca-053cd2573131">

2) Keys pressed: git`<space>`add`<space>`--all`<enter>`. git`<space>`commit`<space>`-m<`space>`”Fixed methods”. git`<space>`push

3) For the commands:
git add : adds all changes to the commit.
git commit -m "Fixed methods": Commits the changes with the specified commit message.
git push: Pushes the committed changes to my main branch of my GitHub repository.


