# Unit-testing-Mlops-Production-code-with-pytest-tox
This repo replicates Mlops Unit Testing with "Testing" branch for running unit-tests and Development branch for Model Training, Using pytest and tox.

# Note: Do not push changes to Main Branch

- In production, The testers/developers can commit the code to Testing Branch and the unit-testing workflow can be run using a Github Runner / Can be run on any cloud.
- The Developers can use the Development Branch to commit the code and run the workflow using a Github Runner / on cloud.

# Unit Tests workflow
- To replicate the CI pipeline for Unit test clone the Testing branch.

- Make Necessary Changes, Commit and Push to the same Testing Branch.

- Each time you push to Testing Branch it creates a new unit-test workflow.

# Model Training workflow
- To replicate the CI pipeline for Model Training clone the Development branch.

- Make Necessary Changes, Commit and Push to the same Development Branch.

- Each time you push to Testing Branch it creates a new unit-test workflow.

#Conclusion
 Hope this repo brings up an idea for Unit-testing for MLops. Thank you!