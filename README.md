Django playground
# Setup Overview
1. Install Python 3
2. Setup VirtualEnv
3. Install the Application
4. Start the Application

## Install Python 3
1. Using [http://brew.sh/](Homebrew) install Python3: `brew install python3`
2. Test the installation by running `which python3` 

## Setup VirtualEnv
1. Using `pip3` install the [virtualenv](https://virtualenv.pypa.io/en/latest/userguide.html) package
  `pip install virtualenv` 
2. Create a directory for the virtual environment inside of your repository
  `mkdir ~/<repo_name>/env/`
4. Move to the directory for the virtual environment 
  `cd ~/<repo_name>/env/`
5. Make the virtual env by calling"
   `virtualenv .`
6. Activate the virtual environment
  `source bin/activate`
  Note: this changes your $PATH enviroment variable to be the virtualenv's `bin/` directory. 
  To deactivate/undo the changes run `deactivate`

## Install the Application
1. Assuming the virtualenv is activate, run `pip install ~/<repo_name>` This will install django, mysql drivers, and everything necessary for this python application
2. Test the application works by calling: `#TODO fill this in`
