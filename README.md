# Multi_type_Transferable_Method
Since the data file uploaded to github is too large, the following two steps need to be run

First, you need to run DataProcessing.py to obtain embedding of node2vec in four datasets
```python
cd Datasets
python DataProcessing.py
```
Second, you need to run MTTM.py
```python
cd ..
python MTTM.py
```