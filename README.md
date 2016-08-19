# Zero-shot learning codes & data
You can now download the codes (SynC.zip):
https://www.dropbox.com/s/astjerjdgcfc5e7/SynC.zip?dl=0

You can also download a baseline method ConSE (ConSE.zip):
https://www.dropbox.com/s/oltpprntkjjspgn/ConSE.zip?dl=0

We provide the GoogLeNet features for three datasets (AwA, CUB, and SUN) in SynC.zip.

Note that on SUN, which has 717 classes in total, we split into ~646 seen classes and ~71 unseen classes, following Lampert et al., PAMI 2014. This is a much harder task than some other work that tests on only 10 unseen classes. The results of our method on such a simpler task are in the Suppl., where we have accuracy around 90%.

Feel free to contact me and let me know if you have any question about the codes.
(Email: weilunchao760414@gmail.com)

# Extra details
Here we provide extra details for our CVPR 2016 paper:

Soravit Changpinyo, Wei-Lun Chao, Boqing Gong, and Fei Sha, "Synthesized classifiers for zero-shot learning," CVPR, 2016.

You can find links to our paper and the supplementary material via

http://www-scf.usc.edu/~schangpi/index.html

http://www-scf.usc.edu/~weilunc/index.html

## Class splitting and semantic information for ImageNet
We provide the details of classes (seen, 2-hop, 3-hop, All) for the ImageNet zero-shot learning task as well as the word vectors in ImageNet_w2v.zip

You can also download it from https://www.dropbox.com/s/f9p3u6883xmt58k/ImageNet_w2v.zip?dl=0

## Features for ImageNet
For extracting the GoogLeNet features, we follow:

http://nbviewer.jupyter.org/github/BVLC/caffe/blob/master/examples/00-classification.ipynb

The name of the network should be [CAFFE_ROOT] + 'models/bvlc_googlenet/bvlc_googlenet.caffemodel'.

Note that for the 1000 seen classes, we extract features from images in ILSVRC2012. For the 20842 unseen classes, we extract features from images in ImageNet2011release.
