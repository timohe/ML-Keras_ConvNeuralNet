# ML-Keras_ConvNeuralNet
Python Code for the FS 2018 Course Machine learning for Managers


## Install Dependencies on MacOS
As there is a problem with older Tensorflowversions (the ones installed by Anaconda Navigator)
https://github.com/keras-team/keras/issues/9621
It is needed to install the dependencies (tensorflow and keras using pip)

source activate environmentXY     
pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.8.0-py3-none-any.whl    
pip install keras    

## To run
Install the requirements from the yml file, maybe `source deactivate;` needed instead of activate.
```
source activate myenvironment;
conda env update -f environment.yml; #use path to env file   
```
3. Use a jupyter notbook with a python 3.5 environment.
