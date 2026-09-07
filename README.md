 # Faster Projected GAN

Unofficial PyTorch implementation of Faster Projected GAN introduced in the paper [Faster Projected GAN: Towards Faster
Few-Shot Image Generation](https://arxiv.org/abs/2403.08778v1).

## Results
Results on the AnimalFace-cat dataset (160 images) provided by the authors of FastGAN :

<div align='center'>
 <img alt="Results in AnimalFace-cat of 160 data" width=450 src="outputs.gif">
</div>

## Introduction
A deep learning model designed for few-shot image generation. It trains rapidly and yields high-quality images, even with a limited dataset (e.g., fewer than 100 samples).

## Installation
1. Clone repo

```bash
git clone https://github.com/diarimandimby/Faster-Projected-GAN/
cd Faster-Projected-GAN
```

2. Install requirements
```bash
pip install -r requirements.txt
```

## Using Faster PG in your own project
```
from discriminator import ProjectedGANDiscriminator
D = ProjectedGANDiscriminator()
```

```
from generator import FasterProjectedGANGenerator
G = FasterProjectedGANGenerator()
```

For a quick start, try the [Colab notebook](https://colab.research.google.com/drive/1szFFNKWGomsLt4-95aFGVxg8suv4J7jK)

## Citation
```bibtex
@misc{liu2021fasterstabilizedgantraining,
      title={Towards Faster and Stabilized GAN Training for High-fidelity Few-shot Image Synthesis}, 
      author={Bingchen Liu and Yizhe Zhu and Kunpeng Song and Ahmed Elgammal},
      year={2021},
      eprint={2101.04775},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2101.04775}, 
}
```
```bibtex
@InProceedings{Sauer2021NEURIPS,
  author         = {Axel Sauer and Kashyap Chitta and Jens M{\"{u}}ller and Andreas Geiger},
  title          = {Projected GANs Converge Faster},
  booktitle      = {Advances in Neural Information Processing Systems (NeurIPS)},
  year           = {2021},
}
```
```bibtex
@misc{wang2024fasterprojectedganfaster,
      title              = {Faster Projected GAN: Towards Faster Few-Shot Image Generation}, 
      author             = {Chuang Wang and Zhengping Li and Yuwen Hao and Lijun Wang and Xiaoxue Li},
      year               = {2024},
      eprint             = {2403.08778},
      archivePrefix      = {arXiv},
      primaryClass       = {cs.CV},
      url                = {https://arxiv.org/abs/2403.08778}, 
}
```
If this repo is helpful, please help to ⭐ it or recommend it to your friends 😊.
