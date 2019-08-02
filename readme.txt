1.  Make a new Laravel site.

2.  Generate the authentication.

3.  Create a database seed that inserts 50 users

4.  Create a new model called car and add 3 properties to it: Make, Model, and year

5.  Create a factory for cars that sets the make field to either ford / honda / toyota

6.  Create a database seed to generate 50 cars.

7.  Create a controller, route, and view to show a contact form and add it to the main menu of your site.

8.  Create a controller, route, and view to show an about page and add it to the main menu of your site.

Unit tests - Each unit test uses an Assertion to check if it was done.

1.  Write a feature test to check if the register return a 200 status code.

2.  Write a feature test to check if the login pages return a 200 status code.

3.  Write a feature test to check if your about page returns a 200 status code.

4.  Write a feature test to check if your contact page returns a 200 status code.

5.  Create a unit test to insert a user into the users table.

6.  Create a unit test to update the name of a user in the database to Steve Smith.

7.  Create a unit test to delete a user in the database.

8.  Create a unit test to count the number of records inserted by the database seed.  i.e. $userCount = 50

9.  Create a unit test to test inserting a car.

10.  Create a unit test to test updating a car year to 2000.

11. Create a unit test to test deleting a car.

12.  Create a unit test to test to count the number of records inserted by the database seed.  i.e. $carCount = 50

13.   Create a unit test to check if a car's year is an integer.

14.  Create a unit test to check if a car's make is either ford / honda / toyota.

15.  Create a unit tests to check that the model is a string.

Submission instructions

You need to submit a working site on heroku, a link to your github, and a screen shot of your test results.  Put the screen shot(s) of your completed tests in a word document.

Each task in the test should have a commit.  There should be 8 commits for the setup and 15 commits for the unit tests for a total of 23 commits.  Each unit test is worth 6.6 points for a total of 100 points for the test.  Tests that are submitted incorrectly will be given a 0.  If you can't complete one of the commits, you should add a commit that has a message that says you can't do this part of the test.   There MUST be 23 commits in the repository.

How your test is graded...

1st your Github site will be visited to check the correct number of commits.  If there are an incorrect number of commits then you will be given a 0.  If you cannot answer a question, you should commit a message that says you can't do it.

2nd your your site on heroku will be tested to see that it works.

3rd  Your word document of your unit test screen shots will be reviewed.

4th.  Your project will be cloned and the unit tests / seeding will be run to verify your word document is accurate.