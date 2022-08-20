# FSDL2022

|   공부기간   |                 공부목적                  |
| :----------: | :---------------------------------------: |
| 2022.08.08 ~ | ML-product에 대한 이해, torch 모델링 연습 |

- [Course Site](https://fullstackdeeplearning.com/course/2022/)
- [Labs git site](https://github.com/full-stack-deep-learning/fsdl-text-recognizer-2022-labs)
- [lab code]() `ing`

## Lecture1: Course Vision and When to Use ML

### [Lecture](https://fullstackdeeplearning.com/course/2022/lecture-1-course-vision-and-when-to-use-ml/)

- ML-product에 대한 기본 설명

### [Lab 1: DNN in PyTorch](https://fullstackdeeplearning.com/course/2022/labs-1-3-cnns-transformers-pytorch-lightning/)

- pytorch 기본설명
- [notebook](./lab01/lab01_pytorch.ipynb)

### [Lab 2a: PyTorch Lightning](https://fullstackdeeplearning.com/course/2022/labs-1-3-cnns-transformers-pytorch-lightning/)

- `pl.Trainer`, `pl.LightningModule`, `pl.LightningDataModule`, `pl.callbacks`, `torchmetrics` 사용법
- [notebook](./lab02/lab02a_lightning.ipynb)
- `issubclass(pl.LightningModule, torch.nn.Module)`는 True이다. 즉, `torch.nn.Module`을 모두 상속받은 상태이다.

### [Lab 2b: Training a CNN on Synthtic Handwriting Data](https://fullstackdeeplearning.com/course/2022/labs-1-3-cnns-transformers-pytorch-lightning/)

- CNN으로 handwriting data를 분류하는 튜토리얼
- [notebook](./lab02/lab02b_cnn.ipynb)
- `torch.flatten`으로 MLP에 넣을 수 있게 한번에 한줄로 만들 수 있다.

### [Lab 3: Transformers and Paragraphs](https://fullstackdeeplearning.com/course/2022/labs-1-3-cnns-transformers-pytorch-lightning/)

- transformer으로 handwriting data를 분류하는 튜토리얼
- [notebook](./lab03/lab03_transformers.ipynb)

## Lecture2: Development Infrastructure & Tooling

### [Lecture](https://fullstackdeeplearning.com/course/2022/lecture-2-development-infrastructure-and-tooling/)

- ML development에서 사용되는 도구들에 대한 설명
  - Software Engineering
  - DL Framework
  - Distributed Training
  - Resourse Management
  - Experiment & Model Management

### [Lab 4: Experiment Management](https://fullstackdeeplearning.com/course/2022/lab-4-experiment-management/)

- tensorboard, W&B 사용법 (with pytorch lightning)
- [[부스트캠프 Tech Talk] 김봉진 WandB로 Auto ML 뿌수기](https://www.slideshare.net/BoostCamp1/tech-talk-wandb-auto-ml)
- [notebook](./lab04/lab04_experiments.ipynb)
