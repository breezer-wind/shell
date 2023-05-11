### 1 Use test commnad to evaluate a conditional expression
- This will return 0 (true) or 1 (false).
    ``` bash
    test expr
    ```
- -o and -a option
  - -o means or ,either expr1 or expr2 is true will be return true
    ``` bash
    expr1 -o expr2
    ```
### 2 test command is similar with [ ]
- example
    ``` bash
    test -d $HOME/bin || mkdir $HOME/bin
    [ -d $HOME/bin ] || mkdir $HOME/bin
