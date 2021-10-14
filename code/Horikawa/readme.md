# Paper
Horikawa, T., & Kamitani, Y. (2017). Generic decoding of seen and imagined objects using hierarchical visual features. Nature Communications, 8(1).
[ [Paper](https://www.nature.com/articles/ncomms15037), [GitHub](https://github.com/KamitaniLab/GenericObjectDecoding) ]
# Demo program
- [Matlab](https://github.com/KamitaniLab/GenericObjectDecoding/tree/master/code/matlab)
- [Python](https://github.com/KamitaniLab/GenericObjectDecoding/tree/master/code/python)
# Analysis
## Python manual 1
The following packages can be downloaded through the link.
- [bdpy](https://github.com/KamitaniLab/bdpy)
- [slir](https://github.com/KamitaniLab/slir)

Run the following scripts. 
(tested with Python 2.7.13)
<pre>
<code>
$ python analysis_FeaturePrediction.py
$ python analysis_FeaturePredictionMergeResults.py
$ python analysis_CategoryIdentification.py
</code>
</pre>
To visulaize the results, run the following script.
<pre>
<code>$ python createfigure.py</code>
</pre>

The figures will be saved in results directory in PDF format
- createfigure_featureprediction.pdf
- createfigure_categoryidentification.pdf


## Python manual 2
To check the Jupyter Notebook version, run our edited file
(tested with Python 3.8.8)
- Tutorial.ipynb
