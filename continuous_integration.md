- Continuous integration is one of the github actions where coders are able to contribute to the code and git is able to run the code and detect any flaws in our code and perhaps notify them of any code smells.

**Steps**
1. Create a workflow:
   - Involves creating a `.github` folder where we also create a `workflows` folder. A yaml file is created within the workflows folder.
   - The purpose of the yaml file is to trigger github actions where the code is run and if there are problems, github sends a signal to the contributors.
**flake8**: Checks the formatting of the python code

2. To get all your modules in the `venv` to `requirements.txt` run the following:
  `pip freeze > requirements.txt`

3. **Linting**
Python has a convention where it is advisable to format your code to conform to. It is called the PEP-convention. There are modules that can assist to detect code smells (unconventional but running python code) e.g. `pylint`. We are going to use `pylint` to detect these code smells.
To install pylint:
    `pip install pylint`

4. We need to populate the yml file with the required files and/or architecture and then push the code

5. **Adding a badge**
   
