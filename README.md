# Geographically Weighted Regression -- A case study of second-hand housing prices in Qinhuai District, Nanjing

**Course**: Spatial Analysis and Modeling (SE, 856.142)

**Authors**: Boqin Cai (boqin.cai@stud.sbg.ac.at)

![](https://image.arrivalguides.com/1500x600/16/0b0bb142d75e110c1c7c6961f6d2626d.jpg)

[GWR_notebook.ipynb](GWR_notebook.ipynb) is the Jupyter notebook file of the project

[GWR_notebook.slides.html](GWR_notebook.slides.html) is the slides which is converted from Jupyter Notebook using the following command.

    jupyter nbconvert GWR_notebook.ipynb --to slides --post serve  --SlidesExporter.reveal_scroll=True

### Environments:

* Python 3.7
* pandas==1.0.3
* geopandas==0.6.2
* matplotlib==3.2.1
* seaborn==0.9.0
* ipyleaflet==0.12.6
* shapely==1.7.0
* pysal==2.2.0
* statmodels==0.10.1
* mgwr==2.1.1


### Update history

#### 03/06/2020

Fix the error of the explanation of Gaussian and Bi-square kernel.

**Gaussian kernel**: 

![equation](https://latex.codecogs.com/svg.latex?y=e^{-{\frac{x^2}{2b^2}}})

**Bi-Square kernel**:

![equation](https://latex.codecogs.com/svg.latex?y=\begin{cases}%200%20&%20\text{%20}%20x\leq%20-1%20\\\\%20(1-{\frac{x}{b}}^2)^2%20&%20\text{%20}%20-1%3Cx\leq1%20\\\\%200%20&%20\text{%20}%20x%20%3E%201%20\end{cases})
