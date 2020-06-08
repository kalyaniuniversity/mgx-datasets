## MLL Toolkit

---

Python program(s) to be used as reference for preprocessing the <a href="https://github.com/kalyaniuniversity/mgx-datasets/tree/master/MLL/datasets/mll_leukemia.txt" target="_blank">mll_leukemia.txt</a> dataset.
<br/><br/>
How to use them? It's really simple!
<br/></br>
<b>Step 01:</b>&nbsp;Run the `mll-leukemia-preprocessing.py` preprocessing code using python 3<br/>
<b>Step 02:</b>&nbsp;Follow the on-screen prompts<br/>
<b>Step 03:</b>&nbsp;yay!

---

In the dataset, each column represents a sample and each row is an associated attribute label. The class labels are not directly given but instead a separate row is used to denote the class labels. It has three classes. Using this toolkit, the top **`n`** attributes can be chosen by calculating the Standard Deviation. The dataset is transformed by keeping the samples row wise and the attributes column wise. Then each sample is provided the associated class label. The output is provided as a CSV file. The original dataset is also converted from `.txt` format to `.csv` format. The top `n` selected dataset is normalized using Z-Score Normalization.

> Note that now when you run the preprocessor, it also creates two associated files, one where the dataset is converted to proper CSV format and the other where a CSV file of the selected datasets are created.