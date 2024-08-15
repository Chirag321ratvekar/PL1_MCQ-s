# PL1_MCQ-s
All Multiple Choice Question Of PL/1 Language.

IMAGE 1:
1. What is the difference between Based and Define?
MCQ:
a) Based defines a variable relative to a pointer, while Define is used for a variable that already exists.
b) Based is used for file declaration, while Define is used for record layout.
c) Based is used for dynamic memory, Define for constant memory allocation.

Answer: a) Based defines a variable relative to a pointer, while Define is used for a variable that already exists.

2. What are storage classes in PL/1?
MCQ:
a) AUTOMATIC, STATIC, CONTROLLED, and INITIAL
b) AUTOMATIC, STATIC, REGISTER, and VOLATILE
c) VOLATILE, STATIC, CONTROLLED, and ALLOCATED

Answer: a) AUTOMATIC, STATIC, CONTROLLED, and INITIAL

3. What are the file formats supported in PL/1?
MCQ:
a) ASCII, EBCDIC, Binary
b) Sequential, Direct, Indexed, and Mixed
c) Sequential, Indexed, and Relative

Answer: c) Sequential, Indexed, and Relative

4. Why do you need Translate?
MCQ:
a) To convert between different encodings
b) To map character sets
c) To perform string substitution

Answer: c) To perform string substitution

5. How do you include a copybook?
MCQ:
a) COPY statement
b) INCLUDE statement
c) INSERT statement

Answer: b) INCLUDE statement

6. What are the ways through which you pass value to a program from JCL?
MCQ:
a) By using the PARM parameter
b) By using the SYSIN statement
c) Both a and b

Answer: c) Both a and b

7. Difference between main program and a subprogram in PL/1?
MCQ:
a) The main program cannot be called by another program, while a subprogram can.
b) A subprogram does not have a PROC statement.
c) Both execute in the same context.

Answer: a) The main program cannot be called by another program, while a subprogram can.

8. Pseudo Variables in PL/1?
MCQ:
a) They are used for debugging.
b) They act as aliases for other variables.
c) They are system variables provided by PL/1.

Answer: c) They are system variables provided by PL/1.

9. Difference between Do While and Do Until?
MCQ:
a) Do While checks the condition at the start, Do Until checks at the end.
b) Do Until runs the loop at least once.
c) Do While is an infinite loop by default.

Answer: b) Do Until runs the loop at least once.

10. What is not a datatype in PL/1?
MCQ:
a) INTEGER
b) BIT
c) CHAR
d) LIST

Answer: d) LIST

11. How do you handle exception in PL/1?
MCQ:
a) Using the ON statement
b) Using the TRY-CATCH block
c) Using the HANDLE statement

Answer: a) Using the ON statement

12. Picture clause of TIME in PL/1?
MCQ:
a) '99.99.99'
b) 'HH:MM
'
c) 'MM/DD/YYYY'

Answer: b) 'HH:MM
'

13. Explain REENTRANT?
MCQ:
a) A program that can be re-entered and resumed after an interruption.
b) A program that modifies itself during execution.
c) A program that runs indefinitely.

Answer: a) A program that can be re-entered and resumed after an interruption.

14. What are the different clauses in OPTIONS?
MCQ:
a) MAIN, REENTRANT, INTERPRET
b) ENTRY, REENTRANT, STRING
c) MAIN, OPTIMIZE, NOTEST

Answer: c) MAIN, OPTIMIZE, NOTEST

15. What is meant by REORDER option in PL/1?
MCQ:
a) It reorders data in memory.
b) It optimizes loops and instruction sequences.
c) It rearranges fields in a structure.

Answer: b) It optimizes loops and instruction sequences.

16. What type of Dataitem declaration is the following ?DCL A DECIMAL
MCQ:
a) A fixed-point decimal number
b) A floating-point decimal number
c) A variable-length decimal number

Answer: a) A fixed-point decimal number

17. What type of Dataitem declaration is the following ?DCL DD FLOAT(16);
MCQ:
a) A single-precision floating-point number
b) A double-precision floating-point number
c) A quadruple-precision floating-point number

Answer: b) A double-precision floating-point number

18. What will be the output of the below statement?
PUT LIST (50, ‘ ’, ‘abc’, ‘ ’,123.445)
MCQ:
a) 50 abc 123.445
b) 50 , abc , 123.445
c) 50 abc 123445

Answer: a) 50 abc 123.445

19. What is the significance of SKIP in PUT LIST?
MCQ:
a) Skips a line after printing.
b) Skips a space before printing.
c) Skips to a new page.

Answer: a) Skips a line after printing.

20. What will be the output of the below?
NAME1 = ‘IIS’; NAME2 = ‘INFOTECH’; COMPANY_NAME = NAME1 || NAME2;
MCQ:
a) IIS INFOTECH
b) IISINFOTECH
c) INFOTECH IIS

Answer: b) IISINFOTECH

21. What will be the output of the below Arithmetic Function?
FLOOR(3.333)
MCQ:
a) 3
b) 4
c) 3.33

Answer: a) 3

22. What will be the output of the below Arithmetic Function?
CEIL(3.333)
MCQ:
a) 4
b) 3.34
c) 3

Answer: a) 4

23. What will be the output of the below Arithmetic Function?
SIGN(-4)
MCQ:
a) -1
b) 1
c) 0

Answer: a) -1

24. Which of the following is correct code to replace String 'CAT' With 'BAT'?
MCQ:
a) TRANSLATE('CAT','BAT')
b) SUBSTR('CAT', 'BAT')
c) REPLACE('CAT', 'BAT')

Answer: a) TRANSLATE('CAT','BAT')

25. Which of the following is correct output of the code below?
SUBSTR('IIS INFOTECH', 5, 4)
MCQ:
a) INFT
b) INFO
c) OTEC

Answer: b) INFO

26. DATE returns date in the form of ???
MCQ:
a) MM/DD/YYYY
b) YYYYMMDD
c) DD/MM/YYYY

Answer: b) YYYYMMDD

27. Which of the following is correct output of the code below?
DCL A CHAR(2) INIT('AB'); PUT LIST (UNSPEC(A)); --- prints the binary equivalent of 'AB'
MCQ:
a) Binary equivalent of 'AB'
b) 01000001 01000010
c) A0B

Answer: a) Binary equivalent of 'AB'

28. What does the first statement in the code below specify?
DCL A CHAR(2) INIT('AB');
MCQ:
a) Declares and initializes variable A
b) Declares a character array A
c) Declares a procedure A

Answer: a) Declares and initializes variable A

29. Which one of the options is true for the below statement?
DCL A FIXED DEC,B FLOAT DEC; Y = A + B;
MCQ:
a) A will be converted to FLOAT DEC
b) B will be converted to FIXED DEC
c) The statement will cause a runtime error.

Answer: a) A will be converted to FLOAT DEC


``````````````````````````````````````````````````````````````````````````````````````````````
IMAGE 2 :
1. What will be the Output of the below statement?
DCL A FIXED DEC(4); DCL B FIXED DEC(5) INIT(12345); A=B;
MCQ:
a) 1234
b) 12345
c) Error

Answer: c) Error (since A cannot hold 5 digits, a truncation or error occurs)

2. What will be the Output of the below statement?
DCL A FIXED DEC(5); DCL B FIXED DEC(5); DCL C FIXED DEC(5); A=99999; B=88888; C=A * B;
MCQ:
a) 888880000
b) 99999
c) Error

Answer: c) Error (since the product exceeds the maximum value for C)

3. How do you Exit a Loop?
MCQ:
a) EXIT statement
b) LEAVE statement
c) STOP statement

Answer: b) LEAVE statement

4. What does the below statement signify?
DCL DAY NAMES(7) CHAR(10);
MCQ:
a) It declares an array with 7 elements of character strings, each 10 characters long.
b) It declares a variable with 7 characters.
c) It declares a string of 70 characters.

Answer: a) It declares an array with 7 elements of character strings, each 10 characters long.

5. What does the below statement signify?
DCL A(7) CHAR(10); B=A*5
MCQ:
a) Multiplies each element in A by 5
b) Concatenates 5 strings of length 10
c) Error

Answer: c) Error (arrays cannot be multiplied directly like this)

6. What does the below statement signify?
DCL 1 EMP_DET, 2 EMP_NO FIXED DEC(5), 2 EMP_NAME CHAR(20), 2 EMP_SALARY;
MCQ:
a) It declares a structure named EMP_DET with three fields: EMP_NO, EMP_NAME, and EMP_SALARY.
b) It declares an array of employees.
c) It declares an indexed table.

Answer: a) It declares a structure named EMP_DET with three fields: EMP_NO, EMP_NAME, and EMP_SALARY.

7. Which option is true for the following statement?
DCL EMP_DET1 CHAR(100); DCL EMP_DET1 LIKE EMP_DET;
MCQ:
a) EMP_DET1 is a character string.
b) EMP_DET1 is declared as the same structure as EMP_DET.
c) EMP_DET1 is an alias for EMP_DET.

Answer: b) EMP_DET1 is declared as the same structure as EMP_DET.

8. What is Output of the below statement?
DCL A PIC '999'; A=345.54; PUT LIST(A);
MCQ:
a) 346
b) 345
c) 345.54

Answer: b) 345 (since the value is truncated)

9. Is the below statement Correct?
DCL B PICTURE ‘\4y9\’;
MCQ:
a) Yes
b) No

Answer: b) No (The picture clause format is incorrect)

10. What is the output of the below statement?
DCL TODAY CHAR(6); TODAY='080808'; PUT EDIT(TODAY)(P'9/9/9/9/9/9');
MCQ:
a) 080808
b) 08/08/08
c) 080/808

Answer: b) 08/08/08

11. Which of the options is true for Subroutine Procedures?
MCQ:
a) They cannot return a value.
b) They must return a value.
c) They can be invoked using the CALL statement.

Answer: c) They can be invoked using the CALL statement.

12. Which of the options is true for CALL BY REFERENCE?
MCQ:
a) Passes the value of the argument.
b) Passes the address of the argument.
c) Creates a local copy of the argument.

Answer: b) Passes the address of the argument.

13. Which of the options is true for CALL BY VALUE?
MCQ:
a) Passes the value of the argument.
b) Passes the address of the argument.
c) Shares the same memory location.

Answer: a) Passes the value of the argument.

14. What would be the attribute (data type) of result for the below function?
CALC: PROCEDURE(A, B, C) RETURNS(FIXED DECIMAL(7)); RETURN(A+B+C); END CALC;
MCQ:
a) FIXED DECIMAL(7)
b) FLOAT
c) INTEGER

Answer: a) FIXED DECIMAL(7)

15. When a procedure invokes itself, it is said to be ___?
MCQ:
a) Recursive
b) Reentrant
c) Recompiled

Answer: a) Recursive

16. The below statement is used to ___?
OPEN FILE(FILE1) PAGESIZE(50);
MCQ:
a) Specify the page size for printing.
b) Specify the page size for memory allocation.
c) Specify the page size for a file buffer.

Answer: c) Specify the page size for a file buffer.

17. The below statement is used to ___?
OPEN FILE(FILE1) PAGESIZE(50);
MCQ:
a) Open the file with a specified buffer size.
b) Close the file after processing.
c) Open the file for reading only.

Answer: a) Open the file with a specified buffer size.

18. The below statement is an example of?
DECLARE EMPLOYEE FILE INPUT STREAM ENV (options);
MCQ:
a) File declaration with input options
b) Stream declaration for employee records
c) Input buffer for file processing

Answer: a) File declaration with input options

19. Is the below statement Correct?
GET EDIT (EMP_NO , EMP_NAME, BASIC, INDIALLOW, MEDMONTH);
MCQ:
a) Yes
b) No

Answer: a) Yes (The statement is correct for retrieving formatted data)

20. Are the below statements Correct?
GET FILE(filename) EDIT (data list) (format list); PUT FILE(filename) EDIT (data list) (format list);
MCQ:
a) Yes
b) No

Answer: a) Yes (The statements are correct for input and output operations with file)

21. What is the file organization of STUD file declared as below?
DCL STUD FILE OUTPUT INDEXED RECORD;
MCQ:
a) Indexed
b) Sequential
c) Relative

Answer: a) Indexed
