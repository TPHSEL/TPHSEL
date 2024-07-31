//This folder contains 21 datasets.
//List of the datasets is in the paper.
//This folder also contains the code file TPHSEL.cpp
//This folder also contains its executable file TPHSEL
//This code can be run on linux terminal
//You can run executable file directly with following command

./TPHSEL.exe name_of_the_dataset.txt

//or you can create your own executable file with the following command

g++ -std=c++11 TPHSEL.cpp -o TPHSEL.exe

//It is clear from above command that you need to have software of c++11 installed.

//The output will consist of four files.

1. trained_model.txt
2. test_results.xls
3. ensemble_results.xls
4. results within individual hierarchies (levels).

//It is clear from the names of the files that
//First file contains details of the trained models in each hierarchy
//Second file contains test results of each iteration (5 iterations) within ensemble.
//The third file aggregates the results of second file to provide final classification results.

have fun!

