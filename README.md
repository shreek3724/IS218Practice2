# IS218Practice2

## The project purpose
The purpose of this project is to create a baci python claclautor with addition and subtraction capabilities, and applying Pytest to it, as well as a workflow to test the functions, and AAA patterned tests.

## Python version
This project uses 
pytest==8.4.2
Python version 3.12

## Environment creation and activation commands
python -m 
pip install -r requirements.txt
python -m pytest -v. 

## Explain AAA and why generated files are ignored.
AAA stands for Arrange, Act, Assert, meaning to set up inputs and expected result, run the function being tested, and checking if the result matches the expected results.
Generated files are ignored because they are automatically created by Python, the virtual environment, or pytest and do not need to be stored in the Git repository.
.gitignore ensures that only necessary files remain updated, to ensure heavy files are not being constantly reuploaded or maintained. 