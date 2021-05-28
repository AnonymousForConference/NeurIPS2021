# LADA: Look-Ahead Data Acquisition via Augmentation for Deep Active Learning

## Requirements

To install requirements:

```setup
pip install -r requirements.txt
``'

## Training

To train the model(s) in the paper, run this command:

```train
python main.py --data Cifar10 --method LADA
```

## Evaluation

- Data will be downloaded to folder 'data'.
- Result will be recorded to folder 'Results'.


## Pre-trained Models

You can download pretrained models here:

- [My awesome model](https://drive.google.com/mymodel.pth) trained on ImageNet using parameters x,y,z. 

>📋  Give a link to where/how the pretrained models can be downloaded and how they were trained (if applicable).  Alternatively you can have an additional column in your results table with a link to the models.

## Results

Our model achieves the following performance on :

### [Image Classification on ImageNet]

| Model name         | FashionMNIST  | SVHN | CIFAR-10 | CIFAR-100 |
| ------------------ |---------------- | -------------- |
| LADA   |     83.68%         |      75.72%       |     53.45%       |     46.92%       |

>📋  Include a table of results from your paper, and link back to the leaderboard for clarity and context. If your main result is a figure, include that figure and link to the command or notebook to reproduce it. 


## Contributing

>📋  Pick a licence and describe how to contribute to your code repository. 
