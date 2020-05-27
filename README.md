# CypherHacker
command line tool for hacking trivial cyphers in python

How to run:
[] - list of possible arguments
{} - optional arguments
<code>$ python3 (for Linux, >python for Windows) encryptor.py encode --cipher [caesar, vignere] --key [key for the cypher type] {--input-file some_file} {--output-file some_file} - for encryption (if no input file is given, the program asks for the direct user input, the same issue concerns output files)<br>
$ python3 (for Linux, >python for Windows) encryptor.py decode --cipher [caesar, vignere] --key [key for the cypher type] {--input-file some_file} {--output-file some_file} - for decryption<br>
$ python3 (for Linux, >python for Windows) encryptor.py train {--text-file some_file} {--model-file some_file} - for saving default letter-frequency in a rather big text<br>
$ python3 (for Linux, >python for Windows) encryptor.py hack {--input-file some_file} {--output-file ome_file} - for hacking(if no input file is given, the program asks for the direct user input, the same issue concerns output files)<br></code>

