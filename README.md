# FSDL2022

|   공부기간   |                 공부목적                  |
| :----------: | :---------------------------------------: |
| 2022.08.08 ~ | ML-product에 대한 이해, torch 모델링 연습 |

- [Course Site](https://fullstackdeeplearning.com/course/2022/)
- [Labs git site](https://github.com/full-stack-deep-learning/fsdl-text-recognizer-2022-labs)
- [lab code]() `ing`

## Lecture1: Course Vision and When to Use ML

- [Lecture](https://fullstackdeeplearning.com/course/2022/lecture-1-course-vision-and-when-to-use-ml/)
  - ML-product에 대한 기본 설명
- [Lab 1: DNN in PyTorch](https://fullstackdeeplearning.com/course/2022/labs-1-3-cnns-transformers-pytorch-lightning/)
  - pytorch 기본설명
  - [notebook](./lab01/lab01_pytorch.ipynb)
- [Lab 2a: PyTorch Lightning](https://fullstackdeeplearning.com/course/2022/labs-1-3-cnns-transformers-pytorch-lightning/)
  - `pl.Trainer`, `pl.LightningModule`, `pl.LightningDataModule`, `pl.callbacks`, `torchmetrics` 사용법
  - [notebook](./lab02/lab02a_lightning.ipynb)
  - `issubclass(pl.LightningModule, torch.nn.Module)`는 True이다. 즉, `torch.nn.Module`을 모두 상속받은 상태이다.
- [Lab 2b: Training a CNN on Synthtic Handwriting Data](https://fullstackdeeplearning.com/course/2022/labs-1-3-cnns-transformers-pytorch-lightning/)
  - CNN으로 handwriting data를 분류하는 튜토리얼
  - [notebook](./lab02/lab02b_cnn.ipynb)
  - `torch.flatten`으로 MLP에 넣을 수 있게 한번에 한줄로 만들 수 있다.
- [Lab 3: Transformers and Paragraphs](https://fullstackdeeplearning.com/course/2022/labs-1-3-cnns-transformers-pytorch-lightning/)
  - transformer으로 handwriting data를 분류하는 튜토리얼
  - [notebook](./lab03/lab03_transformers.ipynb)

## Lecture2: Development Infrastructure & Tooling

- [Lecture](https://fullstackdeeplearning.com/course/2022/lecture-2-development-infrastructure-and-tooling/)
  - ML development에서 사용되는 도구들에 대한 설명
    - Software Engineering
    - DL Framework
    - Distributed Training
    - Resourse Management
    - Experiment & Model Management
- [Lab 4: Experiment Management](https://fullstackdeeplearning.com/course/2022/lab-4-experiment-management/)
  - tensorboard, W&B 사용법 (with pytorch lightning)
  - [[부스트캠프 Tech Talk] 김봉진 WandB로 Auto ML 뿌수기](https://www.slideshare.net/BoostCamp1/tech-talk-wandb-auto-ml)
  - [notebook](./lab04/lab04_experiments.ipynb)

## Lecture3: Troubleshooting & Testing

- [Lecture](https://fullstackdeeplearning.com/course/2022/lecture-3-troubleshooting-and-testing/)
  - Testing Software
    - Pytest, doctests, Codecov, black, flake8, shellcheck, github action, pre-commit
  - Testing ML Systems
    - Use Expection Testing: test our data by checking basic properties, [Testing ML Example](https://github.com/GokuMohandas/testing-ml#training)
    - Use Memorization Testing: 해당 데이터로 모델 훈련이 잘 되는지 확인하는 것
    - Adapt Regression Testing: 하나의 데이터를 뽑아서 예상되는 결과가 나오는지 확인, loss와 metric을 활용할 수도 있다, loss가 큰 데이터를 살펴보기
- [Lab 5: Troubleshooting & Testing](https://fullstackdeeplearning.com/course/2022/lab-5-troubleshooting-and-testing/)
  - lint, test, torch profile
  - [notebook](./lab05/lab05_troubleshooting.ipynb)

## Lecture4: Data Management

- [Lecture](https://fullstackdeeplearning.com/course/2022/lecture-4-data-management/)
  - Data Sources, Data Exploration, Data Processing, Feature Store, Data Labeling, Data Versiong
- [Lab 6: Data Annotation](https://fullstackdeeplearning.com/course/2022/lab-6-data-annotation/)
  - Loading annotated data and synthesizing data
  - Label Studio
  - [notebook](./lab06/lab06_data.ipynb)

## Lecture5: Deployment

- [Lecture](https://fullstackdeeplearning.com/course/2022/lecture-5-deployment/)
- [Lab 7: Web Deployment](https://fullstackdeeplearning.com/course/2022/lab-7-web-deployment/)
  - [notebook](./lab07/lab07_deployment.ipynb)

## Lecture6: Continual Learning

- [Lecture](https://fullstackdeeplearning.com/course/2022/lecture-6-continual-learning/)
- [Lab 8: Model Monitoring](https://fullstackdeeplearning.com/course/2022/lab-8-model-monitoring/)
  - Gantry (model monitoring, continual learning tool)
  - [notebook](./lab08/lab08_monitoring.ipynb)

## Lecture7: Foundation Models

- [Lecture](https://fullstackdeeplearning.com/course/2022/lecture-7-foundation-models/)
  - Fine Tuning, Transformers, Prompt Engineering, Application
