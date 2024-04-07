## Assignment: Decryption Mission

We've detected an unsecured network and uncovered numbers utilized for encrypting crucial documents. It appears that these numbers might not consistently be generated using sufficiently large prime numbers. Your task, should you choose to accept it, is to swiftly factorize these numbers before the target rectifies this vulnerability on their server. This will enable us to decode the encrypted documents.

### Objective: Factorize All Numbers

Factorize as many numbers as possible into a product of two smaller numbers.

### Instructions:

To run the program, use the following command:
```
factors <file>
```
where `<file>` is a file containing natural numbers to factor, with one number per line.

Assumptions:
- All lines in the file will be valid natural numbers greater than 1.
- There will be no empty lines or spaces before and after the valid number.
- The file will always end with a new line.

Output Format: 
```
n = p * q
```
(one factorization per line)

Note:
- `p` and `q` don’t have to be prime numbers.

Execution Conditions:
- Your program should run without any dependencies. Installation of additional packages won't be possible.
- Time Limit: Your program will be terminated after 5 seconds if it hasn’t completed.

Push all your scripts, source code, etc., to your repository. We will only run your executable `factors`.

Compile C function:
cc -fPIC -shared -o lib_factors_functions.so factors_functions.c