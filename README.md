<img src='imgs/horse2zebra.gif' align="right" width=384>

<br><br><br>

# CycleGAN for augmentation of digital optical microscopy nematode images

I provide CycleGAN application for unpaired image-to-image translation in PyTorch. A image synthesis to provide a higher quality database for model training with deep learning algorithms and thus overcome the scarcity of labelless data in the [SIPLAB laboratory](http://www.ie.tec.ac.cr/palvarado/pmwiki/index.php/Proyectos/Nematodos "SIPLAB laboratory"). 

Three experiments were developed in which the networks have been trained with a new database, generating realistic microscopy nematode images: 

### Experiment 1 results

Nematode silhouette (BLUE) **|** Synthetic nematode (GREEN)
<br>
<img src='CycleGAN/Experiment 1/imgs/exp1.gif' align="left" width=408>
<br><br><br><br><br><br><br><br>

### Experiment 2 results

Nematode silhouette (BLUE) **|** Synthetic nematode (GREEN)
<br>
<img src='CycleGAN/Experiment 2/imgs/exp2.gif' align="left" width=408>
<br><br><br><br><br><br><br><br>

### Experiment 3 results

Nematode silhouette (BLUE) **|** Synthetic nematode (GREEN)
<br>
<img src='CycleGAN/Experiment 3/imgs/exp3.gif' align="left" width=408>
<br><br><br><br><br><br><br><br><br>

## Metrics used
The graphs of the training process were displayed in [Weights & Biases](https://wandb.ai/olivier-j/Agrupaci%C3%B3n%20de%201,%202%20y%204?workspace=user-olivier-j "Weights \& Biases") and the fidelity of the generated images using confusion matrices and perceptual realism, respectively.

## About code
The code was written by [Jun-Yan Zhu](https://github.com/junyanz) and [Taesung Park](https://github.com/taesung), and supported by [Tongzhou Wang](https://ssnl.github.io/).

**CycleGAN: [Project](https://junyanz.github.io/CycleGAN/) |  [Paper](https://arxiv.org/pdf/1703.10593.pdf) |  [Torch](https://github.com/junyanz/CycleGAN)**
<img src="https://junyanz.github.io/CycleGAN/images/teaser_high_res.jpg" width="800"/>

Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks.<br>
[Jun-Yan Zhu](https://people.eecs.berkeley.edu/~junyanz/)\*,  [Taesung Park](https://taesung.me/)\*, [Phillip Isola](https://people.eecs.berkeley.edu/~isola/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros). In ICCV 2017. (* equal contributions) [[Bibtex]](https://junyanz.github.io/CycleGAN/CycleGAN.txt)


Image-to-Image Translation with Conditional Adversarial Networks.<br>
[Phillip Isola](https://people.eecs.berkeley.edu/~isola), [Jun-Yan Zhu](https://people.eecs.berkeley.edu/~junyanz), [Tinghui Zhou](https://people.eecs.berkeley.edu/~tinghuiz), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros). In CVPR 2017. [[Bibtex]](http://people.csail.mit.edu/junyanz/projects/pix2pix/pix2pix.bib)

## Talks
CycleGAN slides: [pptx](http://efrosgans.eecs.berkeley.edu/CVPR18_slides/CycleGAN.pptx) | [pdf](http://efrosgans.eecs.berkeley.edu/CVPR18_slides/CycleGAN.pdf)

CycleGAN course assignment [code](http://www.cs.toronto.edu/~rgrosse/courses/csc321_2018/assignments/a4-code.zip) and [handout](http://www.cs.toronto.edu/~rgrosse/courses/csc321_2018/assignments/a4-handout.pdf) designed by Prof. [Roger Grosse](http://www.cs.toronto.edu/~rgrosse/) for [CSC321](http://www.cs.toronto.edu/~rgrosse/courses/csc321_2018/) "Intro to Neural Networks and Machine Learning" at University of Toronto. Please contact the instructor if you would like to adopt it in your course.

## Prerequisites
- Linux or macOS
- Python 3
- CPU or NVIDIA GPU + CUDA CuDNN