the three-step guide to making model changes

* Change your models (in models.py).
* Run python manage.py makemigrations to create migrations for those changes
* Run python manage.py migrate to apply those changes to the database.

For Git users, in order to track project dependencies, continue below:

* While in the virtual environment, start by installing a package. For this example we will usepandas. Run pip install pandas
* Run deactivate to stop the virtual environment
* Initialize the repo by running git init
* Run echo ‘env' > .gitignore to include the env folder in the .gitignore file so the virtualenvironment is ignored in source control
* Run pip freeze > requirements.txt to place the dependencies in a text file to be committed.Freezing reads all the installed dependencies and then produces a text file with the name of thedependency and the installed version number.
* Run git add requirements.txt to check the file into source control.
* Commit the files and push to a repo.
