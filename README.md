# TestingAzureAutoTests
A playground to try out the automated testing features of Azure DevOps
-made this repo because running the Azure tests on my private repo for Kattis solutions was not passing tests, and it was seriously being a pain
-and I wanted to try out the testing on a functioning repo before I dive into what was causeing the errors in the previous attempt.

Created the repo, and ran the tests... "shockingly" the tests passed when only a README is present

Cloned from GitHub to my local machine

Created a new WpfApplication project, in a random directory

moved the project into the local directory for the repo, and then pushed the code to the remote repo
git add .
git commit -m "..."
git push

re-ran the Azure tests, and they still pass!

Looking at tests that were added into the default pipeline, it is now apparent that  they were not testing any parts of the solution, only echoing
"Hello, world". So now I am going to go through the process of trying to set up an automated test for the code.

Here is a tutorial message. Added tutorial message
Now in Tutorial Branch
