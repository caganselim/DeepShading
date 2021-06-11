## Deep Shading: Convolutional Neural Networks for Screen Space Shading


This repository is a replication of the following paper [ Deep Shading: Convolutional Neural Networks for Screen Space Shading](https://arxiv.org/abs/1603.06078) 


_Oliver Nalbach, Elena Arabadzhiyska, Dushyant Mehta, Hans-Peter Seidel, Tobias Ritschel Deep Shading: Convolutional Neural Networks for Screen-Space Shading to appear in Proc. EGSR 2017_


For the SSIM loss, this implementation is used: https://github.com/jorge-pessoa/pytorch-msssim. Each experiment is in the form of a Jupyter Notebook.

### Dataset

The dataset was available (700GB) during the implementation, however the authors decided to restrict access.

### Requirements

I haven't exported a **requirements.txt** file, but the following setup should be sufficient:

* PyTorch 1.6.0
* PIL  
* Matplotlib
* pyexr