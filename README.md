<!--
Name of your teams' final project
-->
# KNN for Detecting Adversarial Attacks on Computer Networks
## [National Action Council for Minorities in Engineering(NACME)](https://www.nacme.org) Google Applied Machine Learning Intensive (AMLI) at the University of Arkansas

<!--
List all of the members who developed the project and
link to each members respective GitHub profile
-->
Developed by: 
- [Ron Merculief](https://github.com/lrmerculief) - `University of Alaska Anchorage`
- [Abraham Mitchell](https://github.com/Abraham-Mitchell) - `University of Arkansas` 
- [Claudia Mercado](https://github.com/cbaker6) - `University of Arkansas` 


## Description
<!--
Give a short description on what your project accomplishes and what tools is uses. In addition, you can drop screenshots directly into your README file to add them to your README. Take these from your presentations.
-->
1. This program uses data downloaded from https://csr.lanl.gov/data/cyber1/ orignating from the Los Alamos National Laboratory and is put into a pandas DataFrame.
2. The data is labelled from the redteam.txt file by matching the four columns provided to the main DataFrame.
3. This program then utilizes hardcode to gather unique catagories from each column of the main dataset and turns them into unique IDs and scaled to 0 to 1 and put into a dictionary
4. The scaled and labelled data is then split into 5% training data and 1% testing data and fed into K Nearest Neighbor classifier
5. After the model is trained the program predicts the testing data and compares them with a confusion matrix, accuracy, and f1 score
6. The redteam.txt file was used for exploratory data analysis afterward


## Usage instructions
<!--
Give details on how to install fork and install your project. You can get all of the python dependencies for your project by typing `pip3 freeze requirements.txt` on the system that runs your project. Add the generated `requirements.txt` to this repo.
-->
1. Fork this repo
2. Change directories into your project
3. On the command line, type `pip3 install requirements.txt`
4. ....
