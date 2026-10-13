PLP Python Week 6 - Safe Functions
safe_tools.py - three functions (safe_divide, safe_number, get_field) that use try/except so they return a friendly message instead of crashing.
README.md - this file: the assignment title, a description of each file, and the answer below.
Why can the if check not catch abc on its own?

An if check can only test for problems you thought of in advance, and "abc" looks like perfectly normal text: it is not empty and it is a string, so nothing about it fails a simple check. The error only appears at the moment int("abc") actually runs, and try/except is what catches an error at that moment.