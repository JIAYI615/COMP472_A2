# COMP472 Assignment2
## Team name: SmartAI472  

## Contributors

| Name                     | Student ID | GitHub                                          |
| ------------------------ | ---------- | ----------------------------------------------- |
| Xavier Morgan-Tracy      | 40129775   | [XavierKMT](https://github.com/XavierKMT)       |
| Jiayi Chen (Team Leader) | 40110997   | [JIAYI615](https://github.com/JIAYI615)         |
  
## Running instructions:
The assignment contains 2 .ipynb files: task1&task2 and task3  

15 ebooks grouped in 5 folders will be used in training the word2vec model in task3, please make sure those datasets are placed in the same folder with the 4 .ipynb files.  

The synonyms.csv file contains the questions and the answers to test all models used, the answers of each model are saved in separate CSV files with name in the form of 'model-details.csv'  

The file analysis.csv contains the overall performance of all models.  

To run the assignment, please make sure you have the following libraries installed:
```bash
pip install nltk
pip install pandas
pip install matplotlib
pip install gensim
pip install notebook
```
After installing all those libraries, open your terminal and type:
```bash
jupyter notebook
```
The notebook page should be automatically opened in your browser. Cd to the folder and you'll be able to run the 2 .ipynb files. 
