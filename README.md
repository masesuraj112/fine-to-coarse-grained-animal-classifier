This file contains instructions on what each submission file represents and instructions on how to run them.

task1.ipynb - contains all of the relevant code for Task 1 (Relevant machine learning code)

task2.ipynb - contains all of the relevant code for Task 2 (Relevant machine learning code)

experimentation.ipynb - small experiments that I have done - this is not required to be looked at 

The Kaggle test files will be saved to a excel file which will appear in the directory

If confusion matrix is too large, it will saved as a file, otherwise you are able to view it in the jupyter notebook itself 

Instructions on how to run task1.ipynb and task2.ipynb 
- Ensure that task1_data and task2_data folders are stored in same directory location as task1.ipynb and task2.ipynb. Keep it stored in the same way task1_data and task2_data is presented (if task1_data and task2_data is not present in the zip file). This is the reason why -> BASE_DIR = os.getcwd() + "/task1_data/" and BASE_DIR = os.getcwd() + "/task2_data/"

- Once that is set up properly, go to jupyter notebook and for each cell separately click "Run Selected Cell", as clicking "Run All" may cause the code to die/interrupt, make sure to run the cells in order

If the kernel interrupts and requires a restart then run the dataset from the start

Considerations
- Some of the models/feature extractions, may take a while, I have include print statements so you are able to see the progress
- I have installed libraries inside the notebooks as well at times
- Do not run both tasks simulataenously
- Please note that for the Random Forest model in Task 2, the output from Jupyter and the report may be different due to non-deterministic cross-validation runs, however, the numbers only vary a little 



