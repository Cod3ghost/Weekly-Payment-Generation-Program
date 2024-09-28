Highridge Construction Company - Weekly Worker Payment Generation Program
=========================================================================

Overview
--------
This project is designed to automate the weekly payment slip generation process for Highridge Construction Company. It dynamically creates a list of 400 workers, assigns them random salaries and genders, and applies conditional logic to determine their employee levels. The program also handles errors that may occur during execution.

This program is implemented in both Python and R, with detailed exception handling in place to ensure robustness. It is designed to facilitate a smooth, efficient, and scalable process for managing worker payments.

Main Features
-------------
- **Dynamic Worker Creation**: The program generates 400 workers with random salaries and genders.
- **Employee Levels**: 
  - If a worker's salary is between $10,000 and $20,000, they are assigned to Employee Level "A1."
  - If a worker's salary is between $7,500 and $30,000, and the worker is female, they are assigned to Employee Level "A5-F."
- **Payment Slip Generation**: The program generates and prints payment slips for each worker, detailing their ID, salary, gender, and employee level.
- **Error Handling**: Built-in exception handling ensures that any errors encountered during the execution are caught and reported, without stopping the entire process.

Files Included
--------------
1. **Module 1 Assignment - Weekly Payment Generation Program.py**: The Python script to generate worker payment slips.
2. **Module 1 Assignment - Weekly Payment Generation Program.R**: The R script to generate worker payment slips.
3. **README.txt**: This detailed documentation file.
4. **LICENSE**: The licensing details for this project.

How to Run the Program
----------------------
### Python:
1. **Install Python 3.x** if not already installed on your machine.
2. **Run the Python script**:
   - Open a terminal or command prompt.
   - Navigate to the folder where `Module 1 Assignment - Weekly Payment Generation Program.py` is located.
   - Run the following command:
     ```
     python Module 1 Assignment - Weekly Payment Generation Program.py
     ```
3. The script will generate payment slips for 400 workers and print the details to the console.

### R:
1. **Install R** if not already installed on your machine.
2. **Run the R script**:
   - Open the R console or an R development environment like RStudio.
   - Load and run the `Module 1 Assignment - Weekly Payment Generation Program.R` script.
   - The program will generate payment slips for 400 workers and print the details to the R console.

Program Breakdown
-----------------
### Python:
- **Step 1**: A list of workers is dynamically created using a `for` loop, generating a unique ID for each worker.
- **Step 2**: Salaries and genders are randomly assigned to each worker using Python’s `random` library.
- **Step 3**: Employee levels are determined by a set of conditional statements:
  - Workers with a salary between $10,000 and $20,000 are assigned to Level "A1."
  - Female workers with a salary between $7,500 and $30,000 are assigned to Level "A5-F."
- **Step 4**: Payment slips are generated and printed to the console for each worker.
- **Step 5**: Exception handling ensures any potential errors (such as invalid data) are caught and displayed without crashing the program.

### R:
- The R version follows the same logic as the Python code, using R functions such as `sample()` to assign random values and `cat()` to print worker details.

Error Handling
--------------
The program is designed to handle common errors that may occur during execution. Any issues encountered while generating payment slips (such as errors in the data format or other unforeseen issues) will be caught and displayed, allowing the program to continue processing other workers.

Modifying the Program
---------------------
You can easily modify the number of workers, salary ranges, and conditional logic by editing the following sections in the Python or R script:
- **Number of Workers**: Modify the upper limit in the `for` loop (`for i in range(1, 401)` in Python or `for (i in 1:400)` in R).
- **Salary Range**: Modify the ranges passed to `random.randint(5000, 35000)` in Python or `sample(5000:35000, 1)` in R.
- **Employee Level Conditions**: Change the conditions in the `if` and `elif` statements to meet the company's evolving requirements.

License
-------
This project is licensed under the MIT License, meaning you are free to use, modify, and distribute it as long as proper credit is given to the original author.

Contact Information
-------------------
For questions or support, feel free to reach out to Highridge Construction Company’s software development team.

