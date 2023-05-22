Steps:

Step 1: Setup Delete any existing forks of the repository you have on your account
Step 2: Setup Fork the repository
Step 3: The real deal Start the timer!
Step 4: Log into ieng6
Step 5: Clone your fork of the repository from your Github account
Step 6: Run the tests, demonstrating that they fail
Step 7: Edit the code file to fix the failing test
Step 8: Run the tests, demonstrating that they now succeed
Step 9: Commit and push the resulting change to your Github account (you can pick any commit message!)


Step 4: 
  Open terminal through <ctrl> +  <`>
  Type "ssh cs15lp23lp@ieng6.ucsd.edu" then <enter> in terminal.
  
Step 5:
  Copy the SSH link of the forked repository
  In the terminal type "git clone" then <command> + <v> to paste the copied SSH link.
  Press <enter> to clone into ineg6.
  
Step 6: 
  Type "bash test.sh" then <enter> to run the tests
  
Step 7:
  Type "vim ListExamples.java" then <enter> to go into the edit the ListExamples.java file through vim
  Since the code I want to edit is the last index1 of the file, I typed "?index1" then <enter> to go to that line
  Then I typed "e" to place the cursor on the 1 of index1
  Type "r2" to replace the 1 with a 2
  Save and quit the file through typing ":wq!"
  
Step 8: 
  Press <up> <up> because the command "bash test.sh" was 4 up in the terminal's history and so I don't have to write it all up again.
  Press <enter> to run the test again.
 
Step 9:
  Type "git add ListExamples.java"
  Type "git commit -m 'File edited'" 
  Type "git push"
  
