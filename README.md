# fastai02_cat_or_dog_javascript

## Introduction

- This project aims to correctly classify a picture of a dog or cat. 
- This is a FASTAI course [Lesson #2](course.fastai.com) example that classifies whether the image is of a Dog or a Cat. 
- It uses Gradio's API to predict the image. All other code is done with html/javascript. 
- In this case, it classifies the breed of a CAT or DOG :)

## How to Run

- Check out the Huggingface page [here](https://huggingface.co/spaces/casedev/petdetector)
- Check out the Github page [here](https://casedev935.github.io/petdetector_javascript_fastai/)
- Or just run locally clicking in _petdetector.html_

## Technologies used

[![Kaggle](https://www.vectorlogo.zone/logos/kaggle/kaggle-ar21.svg)](https://www.kaggle.com/)

[![Jupyter](https://www.vectorlogo.zone/logos/jupyter/jupyter-ar21.svg)](https://jupyter.org/)

[![Hugging Face](https://www.vectorlogo.zone/logos/huggingface/huggingface-ar21.svg)](https://huggingface.co/)

[![Gradio](https://www.vectorlogo.zone/logos/gradioapp/gradioapp-ar21.svg)](https://gradio.app/)

[![FastAI](https://www.vectorlogo.zone/logos/fastai/fastai-ar21.svg)](https://www.fast.ai/)

[![HTML](https://www.vectorlogo.zone/logos/html5/html5-ar21.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML)

[![JavaScript](https://www.vectorlogo.zone/logos/javascript/javascript-ar21.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Requirements

- FASTAI VISION

## Training the Model

- train.ipynb
- Trained in Kaggle Notebook
- First Jeremy (from FASTAI) used pretrained _CNN RESNET-34_ model
- Then, explored the *CONVNEXT* models using PyTorch's TIMM library
- Settled on the *CONVNEXT_TINY_IN22K* model 
- Fine-tuned in 3 epochs
- Generated model.pkl

## Prediction the Outcome

- Prediction used with Gradio's API endpoint. 




