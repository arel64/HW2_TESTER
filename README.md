# HW2_TESTER
Test for HW2 2023

Clone Repo
Drag kmeans_pp.py,setup.py, c and header files to into the same directoy as test.py
run: python3 setup.py build_ext --inplace
run: python3 test.py

Good output is:

..
----------------------------------------------------------------------
Ran 2 tests in ~Time~s

OK


Any other output should be considered invalid  

Features:  
* Checks many edge cases for input This includes ~25 tests for
* Valid Runs with 4 parameters
* Valid Runs with 3 parameters
* Invalid Runs with 3 paramters
* Invalid Runs with 4 parameters
* Invalid Runs with varing amout of paramters
* This will also check that all 3 inputs provided return the **CORRECTED** output provided
* Maybe something else I forgot
* You may add tests to the tests.txt file, infer how to do it yourselves, if you do please Pull Request so others may use them

Limitations:  
* This script does not check C memory leaks as rami noted that it's not needed/unexpected of us (Look in fourm don't take my word for)
* Maybe something else I forgot
* I tested all of this on WSL Ubuntu 22.04 , It may not work on nova at all.

******
Use at you own risk, I can't say for sure this will work or detect any bugs
******