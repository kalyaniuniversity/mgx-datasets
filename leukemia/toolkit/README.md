## leukemia Toolkit

---

Python program(s) to be used as reference for preprocessing the <a href="https://github.com/kalyaniuniversity/mgx-datasets/tree/master/leukemia/datasets/leukemia.txt" target="_blank">leukemia.txt</a> dataset.
<br/><br/>
How to use them? It's really simple!
<br/></br>
<b>Step 01:</b>&nbsp;Run the `leukemia-preprocessing.py` preprocessing code using python 3<br/>
<b>Step 02:</b>&nbsp;Follow the on-screen prompts<br/>
<b>Step 03:</b>&nbsp;yay!

---

In the dataset, each row represents a sample and each column is an associated attribute label. The first column denotes the class label. Using this toolkit, two types of preprocessing can be performed. In both the cases, the top **`n`** attributes can be chosen by either calculating the Signal to Noise (SNR) value for the two classes or simply by calculating the Standard Deviation. The output is provided as a CSV file. The original dataset is also converted from `.txt` format to `.csv` format. The top `n` selected dataset is normalized using Z-Score Normalization.

> Note that now when you run the preprocessor, it also creates two associated files, one where the dataset is converted to proper CSV format and the other where a CSV file of the selected datasets are created.