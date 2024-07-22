# Recursive-Summarization-for-Long-Biomedical-Documents

This is a repo created for a project based on SemEval shared task with the task page (https://biolaysumm.org/#dates) and task paper (https://arxiv.org/pdf/2210.09932.pdf) openly accessible.

The goal of this project is to benchmark and suggest that shorter input length models (1024 tokens) like Bart are not only resource efficient, which means it's accessible for smaller researche projects, but also competent when compared to longer input models (4096 tokens). As a result, we ran all 6 selected models (3 short input, 3 long input) on Colab with the same GPU and run time limit. As a result, our works on done in Jupyter Notebooks and are recommended to be run on Google Colab as a lot of our stored dataset, generated abstracts, and evaluation result are stored in my shared drive. We also didn't use the entire PubMed dataset but just a fraction (20k) due to limited runtime. 
