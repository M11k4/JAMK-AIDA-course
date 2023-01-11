## 3-1) List calculation for numbers only

Write a program that calculated sums and averages for the numbers in the list.

Calculate sum and average of elements in the list
Just ignore all values in the list that are not numbers but count all numbers (int or float) in the list.

Initialize the list with the following values

    nlist = [1, 2, 3, 4, 5, 6, 7, 8, 9, 20, 30, "aa", "bee", 11, "test", 51, 63, 11.1]

Then create these functions which calculates sum and average for the list

    my_sum = calc_sum(nlist)
    avg = calc_avg(nlist)


An Example of Program Execution which uses the given list:

    Sum 231.1 and average 15.406666666666666

## 3-2) System environment variables

Write a program that print all environment variables in the current operating system.

Print all system environment variables in your system.
Use `os` module and it's `environ` dictionary for that.

An Example of Program Execution from the Local computer:

    python model_03_02_os_env.py
    ALLUSERSPROFILE => C:\ProgramData
    COMMONPROGRAMFILES => C:\Program Files\Common Files
    COMMONPROGRAMFILES(X86) => C:\Program Files (x86)\Common Files
    etc.

## 3-3) Finnish-English dictionary

Write a program that created Finnish-English dictionary.

* Create a simple finnish-english dictionary.
* Give a finnish word as an input and try to find matching english word.
* If word is not found return `None`.

An Example of Program Execution:

    Give a Finnish Word>kissa
    cat
    Give a Finnish Word>koira
    dog
    Give a Finnish Word>kettu
    None
    Give a Finnish Word>pillipiipari
    None
    Give a Finnish Word>tila
    status

--------------------------------------
3-4) Create Lottery numbers

Write a program that created lottery numbers randomly.

Create a program that randomly generate unique lottery numbers for
* Lotto: 7 unique numbers between 1-39
* Viking: 6 unique numbers between 1-48

An Example of Program Execution:

    python ex_lottery.py
    Lotto: {4, 8, 10, 15, 18, 22, 29}
    Lotto: {35, 4, 5, 7, 11, 23, 31}
    Lotto: {36, 4, 10, 23, 25, 27, 28}
    Viking: {35, 36, 37, 21, 24, 26}
    Viking: {32, 36, 38, 40, 25, 27}
    Viking: {1, 3, 41, 13, 46, 27}

## 3-5) Simulating a shopping queue

Write a program that simulates a shopping queue.

Add new persons to the shopping queue from the list and serve clients in order.
This is only simulating a shopping queue which uses simple list as a data structure.

An Example of Program Execution:

    model_03_05_shop_queue.py
    Simulation starts... Now there are new client in the queue:  ['first', 'second', 'third', 'fourth', 'fifth', 'Bill']
    Serving client  first
    Serving client  second
    Serving client  third
    Serving client  fourth
    Serving client  fifth
    Serving client  Bill
    Queue is now empty
    Simulation starts... Now there are new client in the queue:  ['Less', 'More']
    Serving client  Less
    Serving client  More
    Queue is now empty

## 3-6) Combining and sorting lists

Write a program that first combines several lists into one list and then sort that new list.

Combine these lists in your program.

    first_names = ['Linux', 'Anders', 'Larry', 'Guido', 'Rasmus', 'Pekka', 'Grace', 'Dennis', 'Bjarne']
    last_names =   ['Torvalds', ' Hejlsberg', ' Wall', 'Von Rossum', 'Lerdorf', 'Klärck', 'Hopper', 'Ritchie', 'Stroustrup']
    langs =   ['Linux', 'C#', 'Perl', 'Python', 'PHP', 'Robot Framework', 'COBOL', 'C', 'C++']

Created combination list should be created like this:

    ['Lastname, Firstname', 'Language']
    ['Von Rossum, Guido', 'Python']

Sort (and reverse sort) persons by the programming language they have developed.

An Example of Program Execution:

    Sorted by lang: [['Ritchie, Dennis', 'C'], ['Hejlsberg, Anders', 'C#'], ['Stroustrup, Bjarne', 'C++'], ['Hopper, Grace', 'COBOL'], ['Torvalds, Linux', 'Linux'], ['Lerdorf, Rasmus', 'PHP'], ['Wall, Larry', 'Perl'], ['Von Rossum, Guido', 'Python'], ['Klärck, Pekka', 'Robot Framework']]
    Reversed by lang: [['Klärck, Pekka', 'Robot Framework'], ['Von Rossum, Guido', 'Python'], ['Wall, Larry', 'Perl'], ['Lerdorf, Rasmus', 'PHP'], ['Torvalds, Linux', 'Linux'], ['Hopper, Grace', 'COBOL'], ['Stroustrup, Bjarne', 'C++'], ['Hejlsberg, Anders', 'C#'], ['Ritchie, Dennis', 'C']]

