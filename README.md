# PhDfiles
Repository of the machine learning techniques used for my PhD thesis. This code was written in Jupyter Notebook.

pca_washedtextiles uses an arbritrary csv file 'file_name.csv'. This file should be a data matrix of the format (xy) the horizontal axis labels should be the spectral wavenumbers/wavelength and the vertical axis should be the groupings of the spectra. 

pca_washedtextiles allows the analysis of spectral data using Principal Components Analysis. In order to determine the appropriate number of principal components, the data matrix was randomised and pca was run, the eigenvalue for this PCA was added to a list. This was repeated 999 times. An average eigenvalue was found from the list, the resulting eigenvalue was used as a marker for which principal component to used. 

All _cluster files describe methods to cluster the PCA found using pca_washedtextiles. 
