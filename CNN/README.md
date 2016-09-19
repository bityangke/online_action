A DEMO code that enables to run RGB CNN net to generate frame predictions.

Setup
=====

##### Install caffe
* Build caffe and pycaffe. The instructions for installing caffe are [here](http://caffe.berkeleyvision.org/installation.html).

##### Download the datasets and pre-trained models
* [Caffe model](http://caffe.berkeleyvision.org/installation.html) trained on tvseries dataset train split, download into model folder.


Testing
=======

* Evaluate on a dataset split
```Shell
python demo_CNN.py
```
(You may have to change the python script according to your own local path)