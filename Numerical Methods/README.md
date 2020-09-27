# Numerical Methods

- It is a method that helps us to implement the numerical problems into the computer.

## Fundamental concept of Numbers

- There are two types of numbers
    - **Exact numbers :** Those numbers which are used as precise as they are initially. `Ex: 3, 35.5, etc`
    - **Approxaimate numbers :** Those numbers which are used after rounding off or chopping off their initail values down to small digits. `Ex: Pi = 3.1415, etc`

### Significant figures

- It is the numbers of digits used to express a number
- `Example: 7845, has 4 significant digits`
- `0`'s are counted as significant digits only if they are inbetween other numbers.
    - `Example: 0056, has 2 significant digits`
    - `6098, has 4 significant digits`
    - `98700, has 3 significant digits`

### Rounding off

- The process of dropping unwanted digits after decimal points to some significant digits.
- `Ex: 3.1214361 can be rounded up to 4 significant digit as 3.1214`
- If the digit after the digit that is rounded is equal or greater than 5 then the rounding digit is added with 1.
    - `Ex: 4.131657 can be rounded upto 4 significant digit as 4.1317`

## ERRORS

- Mistakes that occurs in process of solving a numerical problem.
- 3 types of error, they are:-

### 1, Inherent Error

- Errors which are already present in the statement of a problem before its solution.
- Such errors is caused either due to given data being approximate or due to limitations of mathematical table, calculators, or digital computers.

### 2, Rounding Error

- Errors which is arised from the process of rounding of the numbers during the computation.
- Such errors are unavoidable in most of the calculations due to the limitation of computing devices.

### 3, Truncation Error

- Errors ehcih is arised due to the usage of approximate results or replacing infinite process by a finite one.
- If we use a decimal computer having a fixed length of 4 digits, then trauncation error is occured.

## Measures of Error

- If X is the true value of a quantity, and X' is its approximate value, then
    - **Absolute Error(Ea):** | X - X' |
    - **Relative Error(Er):** | ( X - X' ) / X |
    - **Precntage Error(Ep):** | ( X - X' ) / X | * 100%