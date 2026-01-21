# Neural-Network-based-Solver
Code for "Neural Network Surrogates Enable Robust and Accessible Modeling of Renal Epithelial Transport"

There are three Jupyter notebooks.

cell-state NN.ipynb trains and validates the baseline model that predicts cytosolic [Na] and [K], and apical and basolateral membrane potentials, given transporter parameters. Four input features, four output variables. You can specify the sex and segment type by setting the variables at the beginning of the notebook.

cell-params. NN.ipynbtrains and validates the baseline model that infer transporter parameters from given cytosolic [Na] and [K], and apical and basolateral Na fluxes. It is very similar to cell-state NN.ipynb.

cell-inhib NN.ipynb basically trains the same NN cell-state NN.ipynb would, but uses it to predict cellular conditions when one of the transporteres is inhibited. Again, it is very similar to cell-state NN.ipynb.
