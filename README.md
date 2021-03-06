<img src='docs/cont_nema.png' align="right" width=360>

<br><br><br><br><br><br><br><br><br><br><br>

# CycleGAN for augmentation of digital optical microscopy nematode images

I provide CycleGAN application for unpaired image-to-image translation in PyTorch. A image synthesis to provide a higher quality database for model training with deep learning algorithms and thus overcome the scarcity of labelless data in the [SIPLAB laboratory](http://www.ie.tec.ac.cr/palvarado/pmwiki/index.php/Proyectos/Nematodos "SIPLAB laboratory"). 

Three experiments are developed in which the networks have been trained with a new database, generating different quality grades of realistic microscopy nematode images: 

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
The graphs of the training process are displayed in [Weights & Biases](https://wandb.ai/olivier-j/Agrupaci%C3%B3n%20de%201,%202%20y%204?workspace=user-olivier-j "Weights \& Biases") and the fidelity of the generated images using confusion matrices and perceptual realism, respectively.

## About code
The code was written by [Jun-Yan Zhu](https://github.com/junyanz) and [Taesung Park](https://github.com/taesung), and supported by [Tongzhou Wang](https://ssnl.github.io/).

**CycleGAN: [Project](https://junyanz.github.io/CycleGAN/) |  [Paper](https://arxiv.org/pdf/1703.10593.pdf) |  [Torch](https://github.com/junyanz/CycleGAN)**
<img src="https://junyanz.github.io/CycleGAN/images/teaser_high_res.jpg" width="800"/>

Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks.<br>
[Jun-Yan Zhu](https://people.eecs.berkeley.edu/~junyanz/)\*,  [Taesung Park](https://taesung.me/)\*, [Phillip Isola](https://people.eecs.berkeley.edu/~isola/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros). In ICCV 2017. (* equal contributions) [[Bibtex]](https://junyanz.github.io/CycleGAN/CycleGAN.txt)


Image-to-Image Translation with Conditional Adversarial Networks.<br>
[Phillip Isola](https://people.eecs.berkeley.edu/~isola), [Jun-Yan Zhu](https://people.eecs.berkeley.edu/~junyanz), [Tinghui Zhou](https://people.eecs.berkeley.edu/~tinghuiz), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros). In CVPR 2017. [[Bibtex]](http://people.csail.mit.edu/junyanz/projects/pix2pix/pix2pix.bib)

## Talks
Thesis slides: [pdf](https://drive.google.com/file/d/1Y0e3I6Rxdajq4lwMQUTEQ-Iqa0rNZmQN/view?usp=sharing)

Final graduation thesis report: [pdf](https://drive.google.com/file/d/1I8zBjsXpmPfnJPUqp3m5_AQop7Ef4NHr/view?usp=sharing)

