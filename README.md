# FASTA to Single-Line
A lightweight and accessible Python script that offers a straightforward and efficient solution to convert FASTA-formatted files, commonly utilized in bioinformatics, into a single-line format. 
This conversion streamlines data processing and analysis, enabling easier handling and manipulation of biological sequence data.



## Getting Started

### Dependencies

The script relies on the following Python modules:

'argparse': For command-line argument parsing.

'os': For file-related operations.

### Installing

No specific installation steps are needed since the script uses standard Python libraries. Ensure you have Python installed on your system (preferably Python 3.0 or greater).

### Executing program

*Open a terminal or command prompt.

*Navigate to the directory containing the script.

*Enter the command as follows: 

(For Single-File Use)
```
python FASTACMD.py -i <input_file1> -o <output_file>
```
(For Multi-File Use) 
```
python FASTACMD.py -i <input_file1> <input_file2>  -o <output_file>
```
*note* - If -o flag is not used, a generic name will be used to label the output file 

(For single-file use (with GUI))
```
python FASTAGUI.py
```
and select file for input and output

## Author



Nathan Do

 -nayth0s5@gmail.com

This project is licensed under the MIT License - see the LICENSE.md file for details
