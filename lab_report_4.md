# Lab Report 4
## Step 1: Login
- Press CTRL-R ssh then ```Enter```. CTRL-R helps search for previous commands that you use and makes it easier and faster to work in the terminal. 
- ![Image](1.png)

## Step 2: Clone
- CTRL-R git then ```Enter```. We will use _git clone_ to clone the git repository.
  ![Image](2.png)
- Clone the repository
  ![Image](2.0.png)

## Step 3: Run the tests
- ```<Up><Up><Up><Up><Up><Up><Up><Up><Up><Up><Up><Up>``` - Until I found the command I used previously to run the JUNIT tests.
- ```<Backspace><Backspace><Backspace><Backspace><Enter>``` - I edit the name of the file so that I can run the tests.
  ![Image](failedtest.png)

## Step 4: Edit the code
- Enter ```nano ListExamples.java``` to open the file in the terminal and edit it.
- Then, I fixed the code by changing _index1_ to _index2_
  ![Image](code.png)

## Step 5: Test again
- ```<Up><Up><Up><Up><Up><Up><Enter>``` to reach junit command ```javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java```
- ```<Up><Up><Up><Up><Up><Up><Enter>``` to reach junit command ```java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTest```
- We can see that the tests pass now:
  ![Image](testworked.png)

## Step 6: Commit and Push
- Enter ```git add ListExamples.java``` to add the edited file.
- Now, type ```git commit -m "fixed_file"``` to save the changes made to the file.
- Finally, push the file so that it becomes available on git: ```git push```
  ![Image](last.png)
  
- At first, I took _12 minutes_ to do it, but by the last try I took only _1 minute and 48 seconds_.
