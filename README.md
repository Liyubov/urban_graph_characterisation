# Urban graph characterisation

Urban module to work with clustering of graphs.
Notebooks, to each of the task of the module (Модуль ФД1):


1. Сlustering of urban graph. We use several algorithms (Girvan-Newman, Louvain, Spectral Clustering, Label Propagation). We download the data from osmnx module. Notebook ФД1_clustering_graph.ipynb https://github.com/Liyubov/urban_graph_characterisation/blob/main/notebooks/%D0%A4%D0%941_clustering_graph.ipynb 
2. Classification of graph into urban / sub-urban types: challenge here is that different urban graphs have different measures. We test this on city graphs applying approach on various graph types. For this we first make a) characterisation of graph properties, see notebook ФД1 модуль dataset analysis.ipynb, b)applying GNN types of classification. 
3. Recommendation of properties of urban graphs given the selected type (urban / sub-urban) or land-use area. 


## Data 

Data are located in the folder town_suburb_village.zip and downloaded from osmnx given the city attribute. 
More data can be loaded using the code from https://github.com/romanroff/Job/blob/main/notebooks/download_graphs.ipynb
Ready to use and train the data you can use the data from 
https://github.com/Liyubov/urban_graph_characterisation/blob/main/town_suburb_village.zip

# Описание алгоритмов с osmnx urban graph characterisation 

1. Скачать или сгенерировать данные городов с osmnx.
2. Выделить подграф из графа данных (osmnx).
    Кластеризация подграфа по типу (urban / sub-urban / periphery... )
3. Рекоммендовать измененные новые свойства городских графов.

