# Question

In this directory, you have 2 differents notebook: 

- NLP_TP2_01.ipynb which is the notebook about the question-answering model training
- NLP_TP2_02.ipynb which is the notebook about the searchable index

To run and test the code of the different lab please follow these steps:

* Download virtualenv with pip 
```
pip install virtualenv
```
* Create a python environment

```
cd my_project_folder
virtualenv <question-answering>
```
* and activate it:
```
source quetion-answering/bin/activate
```
* Use the requirements.txt file to download and install the dependencies
```
pip install -r requirements.txt
```
* Finally, you can open jupyter notebook:
```
jupyter notebook
```

Once in jupyter, you can select the notebook you want to see.
All notebook are already compiled, but feel free to relaunch any cell you want (/!\ be carefull, the order of the cell is important /!\)

If you have finish to work in the environment, you can desactivate it with:
```
desactivate
```
Finally, you can delete the environment and all the library, you juste have to delete his folder:
```
rm -rf question-answering
```
