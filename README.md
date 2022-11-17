# Class 6 classwork

## Exercise 1 – Using docstrings and doctests. This exercise will show why it is important to keep documentation accurate, and how to do this automatically using docstrings and doctests.

This exercise will show why it is important to keep documentation accurate, and how to do this automatically using docstrings and doctests.

### Setup
Make sure you've had a look at the course notes on documentation so that you understand some of the background around docstrings and doctests
Fork and clone the average_squares repository. (git clone git@github.com:<your_user_name>/average_squares.git)
Open the squares.py file

### Understanding
Spend some time reading and understanding the code.
Do you understand what it's meant to do? Do the docstrings help?
Run the code with the default inputs. Does it produce the output you expect?
Try running the code with other inputs. What happens?

### Exercises
As you may have discovered, the code in squares.py does contain some mistakes. Thankfully the functions in the file include documentation that explains how they should behave.

#### Run the doctests
Use the doctest module to see whether the documentation of the code is accurate: python -m doctest squares.py
Try to understand the structure of the output - what errors are reported, are they what you expected from looking at the code in the previous steps?
#### Update the docstrings
Look at the errors related to the average_of_squares function.
Figure out where the mismatch between the documentation (intended behaviour) and the actual behaviour of the function exists.
Correct usage examples in the average_of_squares function that are incorrect
#### Correct the code and verify
Re-run the code; again comparing the actual and expected behaviour. What is the error?
Correct the error in the code and rerun doctest to confirm that the average_of_squares documentation is now correct
#### Repeat the process for convert_numbers
Look at the doctest error from the convert_numbers documentation.
Can you identify the bug? How would you fix this?

### Submit a Pull Request
Once you have completed or made progress on the exercises

Create a pull request (PR) from your branch to the upstream repository. Add a meaningful title to that PR and a link to this issue: Answers UCL-COMP0233-21-22/RSE-Classwork#30
