# bi-Mean Gaussian Automatic Threshold Selection

## Objective

To take an image's histogram from a text file and find the best threshold using the Gaussian automatic threshold selection method.

This process yields a Gaussian function which will be graphed along with the histogram, and the best threshold on a specified output file

## Usage:

1. Create a new folder
2. Copy noa_adrian_main.cpp into empty folder
3. Copy the BiGuass_data files 1 and 2 into a folder
4. Run the following command

`g++ noa_adrian_main.cpp -o main.exe && ./main.exe BiGuass_data1.txt outFile1-1.txt outFile1-2.txt && ./main.exe BiGuass_data2.txt outFile2-1.txt outFile2-2.txt`

<a href='https://github.com/adrianmnh/CS381-ComputerVision/tree/mainBranch/project3'>Project Repo</a>