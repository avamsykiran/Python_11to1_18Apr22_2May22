Python
---------------------------------------------

    Python Basics, 
    Logic and Conditional Flow in Python , 
    Dictionaries and Sets in Python, 
    Files and Input/Output , 
    Errors and Exceptions , 
    Functions and Modules , 
    Classes and OOP , 
    Python Library: NumPy,
    Python Library: SciPy,
    Python Library: matplotlib,
    Python Library: Pandas,
    --Python Library: Seaborne

    Intro

        Python was developed by Guido van Rossum in the late eighties and early nineties at the National Research Institute for Mathematics and Computer Science in the Netherlands..

        Python is derived from many other languages, including ABC, Modula-3, C, C++, Algol-68, SmallTalk, and Unix shell and other scripting languages

        Easy-to-learn
        Easy-to-read
        Easy-to-maintain
        A broad standard library
        Interactive Mode
        Portable
        Extendable
        GUI Programming
        Scalable

    Lab Setup

        Python  2.7
        VSCode as an IDE / PythonWin as IDE / Pycharm as IDE

    Characteristics

        1. case sensitive
        2. no statement terminator, but each line is assumed to be a single statement.
        3. no block statement either, the blocks are organized as indented statements.
            an indent can be of spaces of any length but 4 spaces is the general standard.
            statements belonging to the same block must have the indent of equal length.

        //java / C#
        if cond {
            statement1;
            statement2;
        }
        statement 3;

        #python

        if cond :
         statement1
         statement2
        statement3

    Tokens

        is the samllest indivisible part of a script or code.

        Identifiers
            are the names givne to program resources liek varialbes, classes, objections, functions ..etc.,

            1. an identifier should start with a letter or _
            2. an identifier can be of any length
            3. an identifier can not contian spaces and special character other than alphabet and digits.
            4. a class identifier is expected to start with a capital letter and all other idenfiers
                are expected start with lower case letters.
            5. if an identifier start with an _ (underscore), it is understood as a private resource
            6. if an identifier start with an __(dbl underscore), it is understood as a strongly private resource
            7. certtain language pre-defiend identifers start and end with _ (unbderscores)

        Keywords
            are reserved word in any language and python keywords are lower in case .

        Operators
            Arithemtic
                    +   addition        sum
                    -   substraction    difference
                    *   multiplication  product
                    /   division        quitiont
                    %   division        reminder
                    **  exponent
                    //  floor division  quitiont

            Relational
                    ==  is equal to
                    !=  is not equal to
                    <   is less than
                    >   is greater than
                    <=  is less than or equal to
                    >=  is greater than or equal to

            Logical Operators
                    and
                    or
                    not

            Assignment Operators
                    =
                    +=      a+=b        a = a+b
                    -=
                    /=
                    *=
                    **=
                    //=
                    &=
                    |=
                    ^=
                    ~=
                    <<=
                    >>=

            Identity Operators
                is              x is Type
                is not          x is not Type

            Memebrship check operator
                in              x in obj
                not in          x not in obj

            Bitwise operators
                &       x = 4 & 7
                            0100 & 0111 = 0100
                |       x = 4 | 7
                            0100 | 0111 = 0111
                ^       x = 4 ^ 7
                            0100 ^ 0111 = 1100
                ~       x = ~4
                            ~0100 = 1011
                <<
                >>

        Comments
                #to give a comment
                """
                    is a multi line string
                    but if not assigned to any variable
                    python ignores it and hence
                    can be used as a mulitline comment
                """

        Literals
                is a hard coded value in an expression.

                c = 2 * PI * r

                    PI is a constant identifier
                    r and c are variable identifiers
                    = and * are operators
                    2 is literal

                integer             0 to 9      12,3,8 
                floating point      .           3.15,5.67
                string              'is a string leteral' , " is also a string letral " 
                                    """
                                            are used for
                                            multi line string
                                    """
                boolean             False,True

    Variables and Data Types

        dynamically typed languages

        x = 56
        y = "Hello World"

        Text Type:	    str
        Numeric Types:	int, float, complex
        Sequence Types:	list, tuple, range
        Mapping Type:	dict
        Set Types:	    set, frozenset
        Boolean Type:	bool
        Binary Types:	bytes, bytearray, memoryview

        type casting:   str(x) will convet int x into a string.

    Control Strucutres

        Branching Statements 

            simple if
                if cond:
                 statements_under_if_block....

            if..else
                if cond:
                 statements_under_if_block....
                else:
                 statements_under_else_block....

            if ladder
                if cond1:
                 statements_under_if_block....
                elif cond2:
                 statements_under_elif_block....
                else:
                 statements_under_else_block....

            inline if
                if cond: single_statement                

            conditional statement
                statement if cond else else_statement

        Looping Statements

            while
            for
        
        Non Condition Statements

            break
            continue

        assignment1: a python script to print the factors of a givne number and check if it is prime
        assignment2: a python script to print a multiplication table from 1 to 20's of a given number

        assignment3: to print only the even positioned elements of a list of strings

        input method
            read a value from the keyboard

        len method
            to retrive the length of a string or a list or any collection.
        
        slicing 
            collection[lb:ub] 
            collection[:ub] 
            collection[lb:]

        assignment4: to accept a userName say('VAMSY') then print it as
            V
            VA
            VAM
            VAMS
            VAMSY

        assignment5: to accept a userName say('VAMSY') then print it as
            VAMSY
            VAMS
            VAM
            VA
            V

        assignment6: to accept a userName say('VAMSY') then print it as
            V
            AA
            MMM
            SSSS
            YYYYY

        
        
        
        


