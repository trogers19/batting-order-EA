# Batting Order Optimizer
BattingOrderEA.pynb contains an evolutionary algorithm developed to optimize a baseball batting order from a given roster.

## Description
Baseball involves an offensive lineup, or batting order, of 9 players. Deciding upon which players to include, and the order in which to include them, in a batting order is a multi-objective task. For this reason, an evolutionary algorithm may be an interesting approach for optimizing a batting order. Iteration 1 of this project shows that an evolutionary algorithm is a feasible approach for a tool to help set a batting order in baseball. The fitness function developed is simple yet effective in encouraging the evolution of appropriate lineups. Results produced show that the algorithm effectively evolves towards more fit batting orders. The final lineups have been qualitatively compared to samples used in games to further assess the performance.

The code here on GitHub is a Python notebook, developed on Google Colab.

This was created by Taylor Rogers as a final project in Biologically Inspired Computation at UTK in Spring 2022. It combines her interests in biologically-inspired algorithms and baseball.

## Requirements
* Python
* [LEAP](https://leap-gmu.readthedocs.io/en/latest/)
* [Pybaseball](https://github.com/jldbc/pybaseball)
* Roster file
  * MIL2021.ROS, included in this repo, was used for development
  * Other roster files may be downloaded from [Retrosheet](https://www.retrosheet.org/) 

**Notes** - If running as a Python notebook, the installation of LEAP and Pybaseball should be included in the first cell of code. On Google Colab, the code will request to connect with your Google Drive. Please be sure to update file paths as necessary, such as that to the roster file.

## Usage
Running the code in Google Colab is highly recommended. Steps for doing so follow: 
1. Navigate to BattingOrderEA.pynb in a browser by clicking on the file name
2. Select  ![image](https://user-images.githubusercontent.com/77810604/185807509-2adf3517-8fa9-4347-ae0d-8589dc1fd0f3.png) to be directed to the Python notebook on Google Colab
3. Run the cells, either all at once or incrementally

## Project Status
This version 1 code was written for a college course. Due to significant time limits, it was developed as a proof-of-concept. There are numerous ways to expand on this, and it should be further advanced for practical use. It is not currently being updated but may be when time allows. Nonetheless, new discussions, issues, or pull requests are welcome.

## Poster and Paper
A conference-style poster and paper in IEEE format were created along with the code as part of a final project. These detail the project's background, related work, data, methods, results, limitations, and further research. Please email troger28@vols.utk.edu if interested in these. 

## Acknowledgements
Thank you to Dr. Catherine Schuman for her encouragement and guidance through this work. It was completed for COSC 420, Biologically-Inspired Computation, at The University of Tennessee, Knoxville.

LEAP, a Python package for Evolutionary Computation, was utilized to develop the evolutionary algorithm for this task.

Pybaseball, an open-source Python package for baseball analytics, was used to scrape sources including Retrosheet, Baseball Reference, and Fangraphs.
