----------------------------------------------------------------------------
for tensorflow error:

ModuleNotFoundError                       Traceback (most recent call last)
Cell In[1], line 4
      2 from random import random
      3 from sklearn.model_selection import train_test_split
----> 4 import tensorflow as tf

ModuleNotFoundError: No module named 'tensorflow'

Use in shell (poetry shell) pip install tensorflow

----------------------------------------------------------------------------
for error LLVM ERROR: Symbol not found: __svml_sqrtf8 wait to update numpy or numba :(

or follow one of both solutions

1. https://github.com/coqui-ai/TTS/issues/3359#issuecomment-1868329035
2. https://github.com/lmcinnes/umap/issues/702#issuecomment-1002396093
