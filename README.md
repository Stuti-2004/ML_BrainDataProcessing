# ML Brain Data Processing

This lab includes two main code files: `ReadVisualizeData.ipynb` and `rf_sex_classification.ipynb`. 

The `ReadVisualizeData.ipynb` notebook is focused on medical imaging visualization. It loads and preprocesses a 3D brain scan in NIfTI format to visualize the scans from various angles including axial, coronal, and sagittal by slicing through the scan's 3D array. Additionally, the code includes an option to binarize images using a threshold, which helps isolate specific regions in the brain data, as a basis for parameter adjustments and observing visualization differences.

The second file, `rf_sex_classification.ipynb`, applies a machine learning classification model to distinguish between male and female subjects based on volumetric brain data. The notebook uses a Random Forest classifier along with a grid search for hyperparameter tuning and k-fold cross-validation to evaluate model performance. 
