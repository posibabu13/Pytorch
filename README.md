# Pytorch
Pytorch Basics
# Intro

PyTorch is a very powerful machine learning framework. Central to PyTorch are tensors, a generalization of matrices to higher ranks. One intuitive example of a tensor is an image with three color channels: A 3-channel (red, green, blue) image which is 64 pixels wide and 64 pixels tall is a  3×64×64  tensor. You can access the PyTorch framework by writing import torch near the top of your code, along with all of your other import statements.

# Why Pytorch

One important question worth asking is, why is PyTorch being used? There is a great breakdown by the Gradient looking at the state of machine learning frameworks today. In part, as highlighted by the article, PyTorch is generally more pythonic than alternative frameworks, easier to debug, and is the most-used language in machine learning research by a large and growing margin. While PyTorch's primary alternative, Tensorflow, has attempted to integrate many of PyTorch's features, Tensorflow's implementations come with some inherent limitations highlighted in the article.

Notably, while PyTorch's industry usage has grown, Tensorflow is still (for now) a slight favorite in industry. In practice, the features that make PyTorch attractive for research also make it attractive for education, and the general trend of machine learning research and practice to PyTorch makes it the more proactive choice.
