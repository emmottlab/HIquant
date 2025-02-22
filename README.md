# HIquant

The Python code in this repository implements the HIquant algorythm for quantifying homologous proteins and proteoforms from bottom up mass-spec data. It is described and tested in:

Malioutov D., Chen T., Jaffe J., Airoldi E., Budnik B., Slavov N. Quantifying homologous proteins and proteoforms bioRxiv PDF | DOI: 10.1101/168765

# Running this code:
This python code is tested on Max OS X 10.15.6 and using Python 3.8.5.

The script can be called from the command line and has 3 required arguments:
1. The input file (see exampleInput.txt)
2. Output file 1 - this has the inferred proteoform abundance
3. Output file 2 - this has the confidence and error estimates for the inference

An example command line call is:
```ed$ python3 ~/Documents/GitHub/HIquant/HIquant_run.py '/Users/ed/Documents/GitHub/HIquant/TestData_fromMCP.txt' '/Users/ed/Documents/GitHub/HIquant/Results/MCP_Output_1.csv' '/Users/ed/Documents/GitHub/HIquant/Results/MCP_Output_2.csv' ``` 
