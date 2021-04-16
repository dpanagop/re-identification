# re-identification
Person re-identification
Python code that:
- crops boxes containig persons from images
- given two such images, decides whether they display the same person or not using a neural network.

Folder min_viable_example contains a Jupyter notebook optimised for Google's colab as Proof of Working example

Please note that the code is written in Tensorflow v1.x
You can use
```python
import tensorflow.compat.v1 as tf
tf.disable_v2_behavior()
```
as stated in this [Stackoverflow thread](https://stackoverflow.com/questions/57614436/od-graph-def-tf-graphdef-attributeerror-module-tensorflow-has-no-attribut) if you have Tensorflow v2.x
