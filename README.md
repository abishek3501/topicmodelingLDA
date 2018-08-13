# topicmodelingLDA
A Tamil topic modelling toolkit using the unsupervised Latent Dirichlet Allocation (LDA) model and Gibbs' sampling.  

Input - A document (test document) containing various topics/labels in various different proportions or probabilities.
Output -
1. The Document-topic distribution i.e, the probability distribution of the topics present in the document.

2. The topic-word distribution i.e, the probability distribution of the words present in the topics. The top words of each                topic present in the document are listed.

Steps to use:
1. Download the .rar file and extract
2. The \src folder contains all the source code required to run the project. 
3. Use Netbeans to import the project and run the file named 'NewJFrame.java' 
4. A small dialog box opens up. First click on delete, to delete the file that has already been in the buffer.
5. Use the Windows file system to graphically search for the test file you wish and select it. 
6. Click on preprocess to preprocess the file and append it to the train corpus to produce the result.
7. Click on generate to run the Gibbs' Sampling modeled LDA.
8. The output is found in the main folder under the file named 'Output.txt'

