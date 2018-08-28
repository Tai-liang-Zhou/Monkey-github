TensorBoard Tutorial
Visualize the training parameters, metrics, hyperparameters or any statistics of your neural network with TensorBoard!


ImportError: cannot import name 'is_list_like'

Because the is_list_like is moved to pandas.api.types, I change the fred.py file which is highlighted in the picture. I replace from pandas.core.common import is_list_like with from pandas.api.types import is_list_like, and it works.
