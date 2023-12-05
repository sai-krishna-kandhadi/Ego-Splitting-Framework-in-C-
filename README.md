# Ego-Splitting-Framework-in-C-

## Project:
Ego-splitting Framework in C++

## Project Type:
Implementation-flavor 

## Paper Link:
https://dl.acm.org/doi/10.1145/3097983.3098054 

## Code Implementation :
C++ 

## Group: 9

## Contributors:
Raj Indroju, Sai Krishna Reddy Kandhadi, Pratyush Reddy Gaggenapalli

## Github URL: 
https://github.com/PratyushGR/Network_science_final_project.git

# Input DataSets: 

Data sets are provided in the Inputs directory we have tested our source code on 4 different datasets

## a. Test
This is a small graph authors have used to explain the framework in the research paper.  Graph with 9 nodes and 11 edges. 
![image](https://github.com/sai-krishna-kandhadi/Ego-Splitting-Framework-in-C-/assets/63501454/21c68a8e-312e-48f1-b088-50b0000943f8)
	
## b. Tv_show edges
Data was collected about Facebook pages (November 2017). These datasets represent blue-verified Facebook page networks of different categories. Nodes represent the pages and edges are mutual likes among them.
![image](https://github.com/sai-krishna-kandhadi/Ego-Splitting-Framework-in-C-/assets/63501454/21fe3389-638b-4684-8eb9-9b946689a87f)


## c. DBLP
The DBLP computer science bibliography provides a comprehensive list of research papers in computer science. We construct a co-authorship network where two authors are connected if they publish at least one paper together. Publication venue, e.g, journal or conference, defines an individual ground-truth community; authors who published in a certain journal or conference form a community. We regard each connected component in a group as a separate ground-truth community. We remove the ground-truth communities which have less than 3 nodes. We also provide the top 5,000 communities with the highest quality which are described in our paper. As for the network, we provide the largest connected component.
![image](https://github.com/sai-krishna-kandhadi/Ego-Splitting-Framework-in-C-/assets/63501454/9bd1a09d-7ff6-4fcd-8fbd-d87973e0d3c5)


# Code Execution
we have implemented our project in C++ from scratch and we have not used any complex libraries any cpp compiler with the right configuration would be able to run our script.

# please follow the below steps before executing the script
##### Step1:
verify your G++ version, download it from https://formulae.brew.sh/formula/gcc or for Vs-code https://code.visualstudio.com/docs/languages/cpp
![image](https://github.com/sai-krishna-kandhadi/Ego-Splitting-Framework-in-C-/assets/63501454/ffd5b902-7640-4faa-9cdf-c8c35c282e6a)

##### step2:
Set the correct Input file path to the "file_name" variable in the main function in ego_split.cpp file to execute our algorithm on the provided data set and plot get the desired split egos for each node

![image](https://github.com/sai-krishna-kandhadi/Ego-Splitting-Framework-in-C-/assets/63501454/a2c3bd50-cba5-4525-908e-2d438bd6771b)

##### step3:
Execute the script and save the output to the log file as the below command

g++ /path/to/file/ego_split.cpp -o /path/to/file/ego_split && /path/to/file/ego_split >> /path/to/log_file/tester_edges.log

