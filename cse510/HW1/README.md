# Setup

Note: Please be sure you have Python installed on your system. The following instructions should work on Mac or Linux. If you have any trouble getting set up, please come to office hours and the TAs will be happy to help.

You can complete this assignment in a virtual environment or locally.

### To set up a virtual environment: 
You might want to create a virtual environment for the project. If you choose not to use a virtual environment, it is up to you to make sure that all dependencies for the code are installed on your machine. To set up a virtual environment, run the following:

	cd assignment1
	sudo pip install virtualenv      # This may already be installed
	virtualenv .env                  # Create a virtual environment
	source .env/bin/activate         # Activate the virtual environment
	pip install -r requirements.txt  # Install dependencies

Once you have completed this assignment, you could exit the virtual environment using the following command line:

	deactivate                       # Exit the virtual environment


### Install requirements (without a virtual environment):
To install the required packages locally without setting up a virtual environment, run the following:

	cd assignment1
	pip install -r requirements.txt  # Install dependencies

# Coding
Please implement the following functions in `vi_and_pi.py`:

	policy_evaluation
	policy_improvement
	policy_iteration
	value_iteration

Write your code between:

	############################
	# YOUR IMPLEMENTATION HERE #

	############################

# Submission
Please submit `vi_and_pi.py` on Canvas.