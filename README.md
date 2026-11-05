
# Calculator lab project
## How to run it
Run: python3 calculator.py
Operations: + - * / (two numbers)

Update 29/10: IT WORKS!!!!

Update 5/11:
(sccm-4910) wongym3@infb079tch032:~/h-drive/calculator$ chmod +x check.sh
(sccm-4910) wongym3@infb079tch032:~/h-drive/calculator$ ./check.sh
=== Calculator quality gate ===
============================= test session starts ==============================
platform linux -- Python 3.12.3, pytest-9.1.1, pluggy-1.6.0 -- /opt/python-venv/sccm-4910/bin/python3
cachedir: .pytest_cache
rootdir: /home/wongym3/h-drive/calculator
collected 4 items                                                              

test_calculator.py::test_add PASSED                                      [ 25%]
test_calculator.py::test_divide PASSED                                   [ 50%]
test_calculator.py::test_subtract PASSED                                 [ 75%]
test_calculator.py::test_multiply PASSED                                 [100%]

============================== 4 passed in 0.03s ===============================
QUALITY GATE PASSED
(sccm-4910) wongym3@infb079tch032:~/h-drive/calculator$ echo $?
0
