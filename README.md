# ANDEquation
#### to run the program, 
### first, copy the ANDEquation.jar file from the directory /out/artifacts/ANDEquation_jar/ to your desired root directory
### second, open the terminal and type the command 

## java -jar ANDEquation.jar  <input.txt> <output.txt>

### The <input.txt> <output.txt> values should either be

####      - an absolute path to the text file or
####      - just the file name. (the program will lookup/save the file in default location)
####          - In this case you need to create a directory named "files" in the root directory, where the jar file is located. 
####          - then create 2 directories in files/ named "input" and "output"
####          *- The default lookup location for the input file is ./files/input/
####          *- The default save location for the output file is ./files/output/

The input (Text) for the AND equation should be one line of comma seperated integer values. For example

{12,8,33,56,8556,1}
