*Maithili Bhide*

### Overall Grade: 89/100

### Quality of report: 8/10

* Is the homework submitted (git tag time) before deadline?

	Yes. `2018-04-27 21:08:28 -0700`.

* Is the final report in a human readable format html? (-2 pts)

	No.  A human readable format like `html` should be submitted along with the `ipynb` file.

* Is the report prepared as a dynamic document (Jupyter notebook) for better reproducibility?

	Yes. `ipynb`.

* Is the report clear (whole sentences, typos, grammar)? Do readers have a clear idea what's going on and how are results produced by just reading the report?

	In general, the report is  clear and easy to follow. Plots in Q4 are beautiful.
 
### Correctness and efficiency of solution: 43/50 

* Q1

* Q2 (-0 pts) 

    Good job!
	
* Q3 (-0 pts)
 
    Good job!

* Q4 (-2 pts) 

    (1), (2): Apparently the expression `y = x^7 - 7x^6 + 21x^5 - 35x^4 + 35x^3 - 21x^2 + 7x -1` is mathematically equivalent to `y = (x - 1)^7`. However the first expression involves sum of terms of alternating signs and incurs **catastrophic cancellation** (substract two nearly equal numbers) (-2 pts)

* Q5 (-4 pts)
	 
     - In your looping function, the looping order is not optimal for Julia. Remember that Julia stores matrix in column-major order. So `ji` looping is better. (-2 pts) 
     - Your vectorization function uses looping. (-2 pts)
     
* Q6 (-1 pts) 

    (4). The `U`, `V` may not be a vector (-1 pts), but the idea works. 



### Usage of Git: 10/10

* Are branches (`master` and `develop`) correctly set up? Is the hw submission put into the `master` branch?

    Yes.

* Are there enough commits? Are commit messages clear? 

    Yes, better with more detailed messages.

* Is the hw1 submission tagged?

	Yes.

* Are the folders (`hw1`, `hw2`, ...) created correctly?

	Yes.	

* Do not put a lot auxillary files into version control.  

	Yes.
		

### Reproducibility: 10/10

* Are the materials (files and instructions) submitted to the `master` branch sufficient for reproducing all the results? 

    Yes

* If necessary, are there clear instructions, either in report or in a separate file, how to reproduce the results?  

    Not applicable for hw1.
    

### Julia code style: 18/20

* Rule (4): 4 spaces for indenting.

* Rule (6): Never place more than 80 characters on a line.

* Rule (7): Always include a single space after a comma. 

* Rule (8):  Never insert a space before a comma.

* Rule (9): Always insert a single space before and after an operator, except for the `^` and `:` operators, which never have spaces around them. (-2 pts)

    -code chunk 226, line 1
    -code chunk 262, line 12

* Rule (12): When naming variables or functions, use short lowercase names if possible.

* Rule (13): If a variable or function name is too long to be read in all lowercase, insert underscores at word boundaries.

* Rule (16): When naming constants, use all caps.
