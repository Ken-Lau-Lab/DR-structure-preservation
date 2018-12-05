### furry-couscous
Review of dimensionality reduction strategies
---
```
pip install -r requirements.txt # make sure you have all necessary python packages
```

#### `fcc_utils.py`
Contains utility functions for reading files and comparing feature-reduced data.  
  
#### `fcc_DRs.py`
Defines classes for manipulation, processing, and visualization of scRNA-seq counts data and dimensionality reduction objects.  
  
__TODO:__
* allow nvr_select to maintain cell and gene IDs (pd.DataFrame)
* suppress plot output in plot_clusters() if clusters not yet assigned
