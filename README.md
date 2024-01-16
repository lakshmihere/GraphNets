# GraphNets
Graph Machine Learning:  Molecular Structure Prediction  | 
-	Graph machine learning is a rapidly emerging field that combines graph theory and machine learning techniques to analyze, model, and make predictions on graph-structured data. 
-	The data for this project comes from Kaggle and it is also available through figshare and also quantum-machine.org.  The data is originally compiled through the following works, 
1.	L. Ruddigkeit, R. van Deursen, L. C. Blum, J.-L. Reymond, Enumeration of 166 billion organic small molecules in the chemical universe database GDB-17, J. Chem. Inf. Model. 52, 2864–2875, 2012. 
2.	R. Ramakrishnan, P. O. Dral, M. Rupp, O. A. von Lilienfeld, Quantum chemistry structures and properties of 134 kilo molecules, Scientific Data 1, 140022, 2014.
-	A subset of the original data was selected at random during pre-processing stages in order to circumvent the long running times.
-	Performed data exploration, data preprocessing, using pandas, numpy, torch, rdkit(cheminformatics toolkit), and other usual packages in python. 
-	The model works alright for small molecules and for larger molecules, the model is not reliable for almost all molecular properties.  A better model is in the works.
Environment: Python, Pandas, Numpy, Scipy, Matplotlib, torch, RdKit, Streamlit, Github.
