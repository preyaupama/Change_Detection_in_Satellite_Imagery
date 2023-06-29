# Change Detection In Satellite Imagery

## Check out the Presentation.pdf and Report.pdf for a quicker overview of the project

This project implement the method of detecting changes in satellite imagery proposed in the paper - de Jong, Kevin Louis, and Anna Sergeevna Bosman. "Unsupervised change detection in satellite images using convolutional neural networks." 2019 International Joint Conference on Neural Networks (IJCNN). IEEE, 2019.

Requirements :
1. Python 3.6.10
2. Jupyter Notebook 6.0.3
3. Following libraries are required to be installed :
      - numpy
      - matplotlib
      - tensorflow
      - skimage
      - Keras
      - pillow
      - scikit-learn
       
      You can install the libraries using -
      'pip install library_name' or 'pip3 install library_name' - depending on the pip command you use to install libraries to        the designated Python.
      
4. System used : macOS Mojave (version - 10.14.6)
5. The entire code was executed in Jupyter notebook within conda(4.7.12) environment
6. The following files and folders must be in the same directory-
      - project_model_train.ipynb [contains code]
      - best_validated_model.hdf5 [pre-trained model]
      - train [contains train data]
      - test_unet [contains test data]
      - augmented_test [contains augmented test data]
      - augmented_train [contains augmented train data]
      
      You will find all these files and folders here : 
      https://drive.google.com/drive/folders/13r7d-GAdcEIHXtBeaa6ERhlzpZKF7CMN?usp=sharing
      You can find the project_model_train.ipynb in this github repository and moodle submission as well
      

Running Instruction:
1. open project_model_train.ipynb using Jupyter notebook
2. Execute code cells one by one except those that have an attached note "----------------DO NOT EXECUTE-------------------". These codes are related to training the model and may take time(6-7 hours) to finish execution, so unnecessary.
3. Some code cells may take 4-5 minutes to finish execution. Thanks for being patient.
3. Observe output from the code cells.

Code Documentation :
Description for each code cell is attached to the cell as a markdown cell.
