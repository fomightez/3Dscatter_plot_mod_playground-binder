[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/3Dscatter_plot_mod_playground-binder/main?urlpath=%2Flab%2Ftree%2Findex.ipynb)

# 3Dscatter_plot_mod_playground-binder
Playground to test 3D scatter plot examples in modern JupyterLab and Jupyter Notebook via Binder

The way I have it set up at this time, launches of sessions from my current [3Dscatter_plot-binder](https://github.com/fomightez/3Dscatter_plot-binder) default to using Jupyter Notbeook Classic (NbClassic).  
I want to see how the notebooks in the series handle modern JupyterLab 4 and Jupyter Notebook 7+ without making two repos with very similar content yet. And hopefully I will find that isn't necessary.       
Currently, other than the text stating things, [3Dscatter_plot-binder](https://github.com/fomightez/3Dscatter_plot-binder) isn't *per se* composed to only run on NbClassic and so it makes more sense for now to use the same content and just have it so I can present the content using the newer software.  
(Note that was very different than the case with what became animated_matplotlib_classic-binder vs. what is now animated_matplotlib-binder with the former being set to work in NbClassic and the latter being for the modern software, and for most part needing very different code and so had to be separate.)

------

##### Only interface-specific issues found so far:

- You have to keep in mind you are in modern JupyterLab or Jupyter Notebook 7+ yourself, despite the text of the current content acting like you should be in old Jupyter Notebook, i.e., NbClassic by default. And so use the approaches I state will work in JupyterLab or Jupyter Notebook 7+, such as `%matplotlib ipympl`

- The link to the Voila 'streamlined 3D scatter plot in Voila interface' on the Index page that comes up, **won't work**. (That only seems to work in the classic interface for now.)   
	Alternatives that will work:  
	In JupyterLab, double-click on the `3D_scatter_Voila_matplotlibSTREAMLINED.ipynb` in the navigation panel to open it. Then after the notebook opens, click on the Voila icon (yellow squigly-over a green line) along the middle of the top toolbar above the running notebook to open it in the Voila rendering. (The Voila icon may appear more towards the right side of the toolbar depending on how large of a windw you have open.)    
	In Jupyter Notebook 7+, click on the Jupyter icon in the upper left side to get to the Jupyter Dashboard. There, double-click on the `3D_scatter_Voila_matplotlibSTREAMLINED.ipynb` in the listing of files. It will open. Then click on the Voila icon (yellow squigly-over a green line) along the top toolbar in the upper left to open it in the Voila rendering.  

##### Concerning 'ipysigma and networkx' here:
- I added ipysigma and networkx when looking into [this SO post](https://stackoverflow.com/q/79098579/8508004), yet was unsuccesful at this point getting it working here, see next bullet point for alternative.
- WORKING OPTION: If you need to use ipysigma and networkx, go [here](https://github.com/fomightez/network-visualisation) and launch a session from there. Unfortunately, it isn't JupyterLab, but works.

------


JupyterLab interface: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/3Dscatter_plot_mod_playground-binder/main?urlpath=%2Flab%2Ftree%2Findex.ipynb)  
Jupyter Notebook 7+:  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/3Dscatter_plot_mod_playground-binder/main?urlpath=%2Ftree%2Findex.ipynb)
