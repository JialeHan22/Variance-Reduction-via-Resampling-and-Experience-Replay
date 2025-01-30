This folder contains the R code to perform the real data analysis for the kernel ridge regression case, provided as Jupyter Notebook files.

The notebook "KRR Real Data R Code.ipynb" contains the code to implement the experiments. The results are stored in txt files according to the following table.

| B \ k/n, n  | k/n=0.5, n=50 | k/n=0.5, n=100 | k/n=0.5, n=150 | k/n=0.5, n=200 | k/n=0.7, n=50 | k/n=0.7, n=100 | k/n=0.7, n=150 | k/n=0.7, n=200 | k/n=0.9, n=50 | k/n=0.9, n=100 | k/n=0.9, n=150 | k/n=0.9, n=200 |
|-----------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|
| B=100      | bos_3.2.1.txt | bos_3.2.2.txt | bos_3.2.3.txt | bos_3.2.4.txt | bos_3.3.1.txt | bos_3.3.2.txt | bos_3.3.3.txt | bos_3.3.4.txt | bos_9.1.1.txt | bos_9.1.2.txt | bos_9.1.3.txt | bos_9.1.4.txt |
| B=300      | bos_5.2.1.txt | bos_5.2.2.txt | bos_5.2.3.txt | bos_5.2.4.txt | bos_7.2.1.txt | bos_7.2.2.txt | bos_7.2.3.txt | bos_7.2.4.txt | bos_9.2.1.txt | bos_9.2.2.txt | bos_9.2.3.txt | bos_9.2.4.txt |
| B=500     | bos_1.2.1.txt | bos_1.2.2.txt | bos_1.2.3.txt | bos_1.2.4.txt | bos_7.1.1.txt | bos_7.1.2.txt | bos_7.1.3.txt | bos_7.1.4.txt | bos_9.3.1.txt | bos_9.3.2.txt | bos_9.3.3.txt | bos_9.3.4.txt |

"KRR Real Data Plot.ipynb" contains the code and results for generating the corresponding variance reduction plots.