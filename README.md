# SCAProtein
Search, concatenate and alignment of protein sequences

## **Prerequired softwares**
Make sure python and biopython are installed.

To install biopython:

		pip install biopython

and if you do not have sudo authority, try:

		pip install --user biopython 

## **Download and Run**

After download and decompress, run the following command to make sure the multiple sequence alignment tool can run:

		chmod +x muscle3.8.31_i86linux64


To run the program:

		python main.py Options subtrate_term_file subunit_term_file 

		Options:

							fetch          Fetch from NCBI by give list

							cat            Concatenate sequences

							align          Run multiple sequence alignment

							all            Run the whole pipeline

							clear          Clear all old files
							
Sample usage:

	python main.py all subtrate.list subunit.list