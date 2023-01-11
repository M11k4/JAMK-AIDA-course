## 2-1) Calculate the sum of command line args

Write a program that calculates sum of command line args,

Create a function which takes numeric list as an argument and validates command line arguments with a function:
def validate_args(numb_list)
 * Numeric values can be have only int or float values. Otherwise, an exception is raised.


    raise Exception(f"'{val}' was not int or float!")

Create a function which takes numeric list as a argument:
  `def count_sum(numb_list)`
* Calculates and returns the sum of given arguments.

An Example of Program Execution from the command line:

    > python model_02_01_sum_cmd_args.py 5.8 6 7 8 9 11 5.6 7 6.7 65 423 342.54
    With args ['5.8', '6', '7', '8', '9', '11', '5.6', '7', '6.7', '65', '423', '342.54'] sum is 897.6400000000001

## 2-2) Arithmetic calculation functions

Create functions which calculate basic arithmetic operations
and which uses default argument values as a last one.

What is default argument:
* Function arguments can have default values in Python.
* User can provide a default value to an argument by using the assignment operator (=).

Functions to implement are:
* `multiply(n, m=2)` # 2nd argument has default value
* `divide(n, m=2)`
* `square_root(n=4)`

How to call functions:

    print(f"Multiply:\t {multiply(2)}\t{multiply(2, 4)}")
    print(f"Divide:\t\t {divide(8)}\t{divide(8, 4)}")
    print(f"Sqrt:\t\t {square_root()}\t{square_root(25)}")

An Example of Program Execution:

    Multiply:	 4	8
    Divide:		 4.0	2.0
    Sqrt:		 2.0	5.0


## 2-3) List Calculation Operations

Create functions that calculate the sum and multiplication
of the both integer list and given `range(a,b)`.

      # numb_list can be list or range
      def multiply_list(numb_list):
    
      def plus_list(numb_list):

How to call functions:

    # Calling functions with list or range parameters - test program:
    range_a = [1, 2, 3, 4, 5]
    range_b = range(6, 11)
    list_a = range(1, 6)
    list_b = [6, 7, 8, 9, 10]
    
    print("Plus List:\t", plus_list(list_a), " ", plus_list(list_b), " ", )
    print("Plus List:\t", plus_list(range_a), " ", plus_list(range_b), " ", )
    print("Multiply List:\t", multiply_list(list_a), " ", multiply_list(list_b), " ", )
    print("Multiply List:\t", multiply_list(range_a), " ", multiply_list(range_b), " ", )

An Example of Program Execution should return:

    Plus List:	 15   40
    Plus List:	 15   40
    Multiply List:	 120   30240
    Multiply List:	 120   30240

## 2-4) sort list of tuples

Sort list of tuples

    pairs = [(1, 'one'), (2, 'two'), (33, 'three'), (4, 'four')]

in the following three ways:

* a) sort based on 2nd value (str) of the tuple
* b) sort based on 1st value (int) of the tuple
* c) reverse sort based on 1st value (int) of the tuple

An Example of Program Execution:

    [(4, 'four'), (1, 'one'), (33, 'three'), (2, 'two')]
    [(1, 'one'), (2, 'two'), (4, 'four'), (33, 'three')]
    [(33, 'three'), (4, 'four'), (2, 'two'), (1, 'one')]

## 2-5) Generator function to create range of float numbers

Create `dec_range()` function similar to range to create numbers from start to end and then enter step as floating point.
`dec_range(start, end, float_step)`

    for x in dec_range(0, 12, 1.2):
        print(x)

Note that there are floating point rounding errors when creating range of `float` numbers. That's not a bug in Python.

An Example of Program Execution:

    0
    1.2
    2.4
    3.5999999999999996
    4.8
    6.0
    7.2
    8.4
    9.6
    10.799999999999999
    11.999999999999998

### 2-5 b) Floating point range without rounding errors.

Try to fix floating point generator function so that there is no any floating point rounding errors.