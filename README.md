# Zero-shot-learning
We provide data and extra details w.r.t. our CVPR 2016 paper

Soravit Changpinyo*, Wei-Lun Chao*, Boqing Gong, and Fei Sha, "Synthesized classifiers for zero-shot learning," CVPR, 2016

You can find links to our paper and the supplementary material via:
http://www-scf.usc.edu/~schangpi/index.html
http://www-scf.usc.edu/~weilunc/index.html

# Class splitting and semantic information
We provide the details of classes (seen, 2-hop, 3-hop, All) for the ImageNet zero-shot learning task as well as the word vectors in ImageNet_w2v.zip

You can also download it from https://www.dropbox.com/s/f9p3u6883xmt58k/ImageNet_w2v.zip?dl=0

# Features
For extracting the GoogLeNet features, we follow:

http://nbviewer.jupyter.org/github/BVLC/caffe/blob/master/examples/00-classification.ipynb

The name of the network should be [CAFFE_ROOT] + 'models/bvlc_googlenet/bvlc_googlenet.caffemodel'.

Note that for the 1000 seen classes, we extract features from images in ILSVRC2012. For the 20842 unseen classes, we extract features from images in ImageNet2011release.
