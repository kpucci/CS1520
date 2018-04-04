# Money on my mind, and my mind on my REST API

Name: Katie Pucci
Pitt ID: kev19

## Installation

1. Create a virtual environment for Python.
2. From the root of the repository run `pip install -r requirements.txt`
3. Add the `FLASK_APP` variable to your path. (e.g. `export FLASK_APP=budget.py`).
4. From the command prompt, run `flask initdb`.

## Running the App

Once installed, the application can be started with `flask run`.

## Notes
- You can't edit or delete the 'uncategorized' category.
- You can't add a category named 'uncategorized'.
- A category won't show its percentage until it's greater than 5%.
- To delete a category, click the edit button and then the delete button.
- Ran out of time to check date input on purchases. Syntax must be "yyyy-mm-dd".
- Added purchase and budget amount checking at last second, so I hope it works!
