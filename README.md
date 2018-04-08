# Project 1-AntlrPractice
use ANTLR to write a lexical analyzer for C code

## How to use 
*   Clone the reposity
    ```
    git clone https://github.com/bobosheep/AntlrPractice.git
    ```
*   If you don't have java, install it
    ```
    sudo apt install default-jre default-jdk
    ```
*   First, create a tokens file and a java file
    ```
    make createTokens
    ```
*   Second, compile the files
    ```
    make compile
    ```
*   Then, you can execute it to test the C code(testCode1~3)
    ```
    /* excution1 for testCode1, excution2 for testCode2 and excution3 for testCode3 */
    make excution1
    make excution2
    make excution3 
    ```

##  Reference
*   [ANTLR](https://www.antlr.org/)