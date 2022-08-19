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

### [Lab 01: DNN in PyTorch](https://fullstackdeeplearning.com/course/2022/labs-1-3-cnns-transformers-pytorch-lightning/)

- pytorch 기본설명
- [notebook](./lab01/lab01_pytorch.ipynb)

### [Lab 02a: PyTorch Lightning](https://fullstackdeeplearning.com/course/2022/labs-1-3-cnns-transformers-pytorch-lightning/)

- `pl.Trainer`, `pl.LightningModule`, `pl.LightningDataModule`, `pl.callbacks`, `torchmetrics` 사용법
- [notebook](./lab02/lab02a_lightning.ipynb)
- `issubclass(pl.LightningModule, torch.nn.Module)`는 True이다. 즉, `torch.nn.Module`을 모두 상속받은 상태이다.

### [Lab 02b: Training a CNN on Synthtic Handwriting Data](https://fullstackdeeplearning.com/course/2022/labs-1-3-cnns-transformers-pytorch-lightning/)

- CNN으로 handwriting data를 분류하는 튜토리얼
- [notebook](./lab02/lab02b_cnn.ipynb)
- `torch.flatten`으로 MLP에 넣을 수 있게 한번에 한줄로 만들 수 있다.

### [Lab 03: Transformers and Paragraphs](https://fullstackdeeplearning.com/course/2022/labs-1-3-cnns-transformers-pytorch-lightning/)

- transformer
- [notebook](./lab03/lab03_transformers.ipynb)

## Lecture2:
