# supervised_algo_analysis
Analysis of various Supervised Learning Algorithms in classification Domain (on two distinct datasets)

Python Notebook: https://github.com/aman-ahluwalia/supervised_algo_analysis.git

Dataset 1 (Breast Cancer Data): https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

Dataset 2 (Wine Data): https://archive.ics.uci.edu/ml/datasets/wine+quality

This project is built on python 3.

You need to install the fast_ai library (which can be done with git clone https://github.com/fastai/fastai.git), all the dependencies can be directly installed using a vitual env with the following command: conda env create -f environment-cpu.yml
This will install all the dependencies needed for the project.
So we can activate this environment using source activate fastai-cpu
Then we can directly run the jupyter notebook.
In the notebook we can add the relative path to the fast_ai library, in my case it was: sys.path.insert(0, "../../../fastai/old/") and can add downloaded data files directly to this directory, if you wish to add somewhere, you need to add the relative path to it.

