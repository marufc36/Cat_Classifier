# Cat_Classifier

## Overview

An image classifier which can classify 20 different breeds of cats based on their image.Those breeds are

1. Abyssinian cat
2. Aegean cat
3. Balinese cat
4. Bengal cat
5. Birman cat
6. Bombay cat
7. British Longhair cat
8. Burmese cat
9. Burmilla cat
10. Cornish Rex cat
11. Cymric cat
12. Donskoy cat
13. Oregon Rex cat
14. Oriental Bicolor cat
15. Persian cat
16. Pixie-Bob cat
17. Ragamuffin cat
18. Siamese cat
19. Siberian cat
20. Turkish Angora cat


## Table of Contents
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Data Collection](#data-collection)
- [Data Modelling](#data-modelling)
- [HuggingFace Deployment](#huggingface-deployment)




## Installation

To get started with this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/marufc36/Cat_Classifier.git
   ```
  
## Dependencies
   ```bash
pip3 install requirements.txt
```


## Data Collection 

In my cat image classifier project, I utilized Python code and the DuckDuckGo browser to efficiently download a diverse dataset of cat images. This approach allowed me to gather a comprehensive collection, ensuring the robustness and accuracy of my classifier in recognizing and categorizing different feline breeds.

```bash
https://colab.research.google.com/drive/1U5Jh2-r1TapSpMT1N2gu77njrEyEnH2G?usp=sharing
```

Training Batch


![image](https://github.com/marufc36/Cat_Classifier/assets/151602012/de44c3c7-4b30-4823-bf54-9e549aee63af)



Validation Batch

![image](https://github.com/marufc36/Cat_Classifier/assets/151602012/4f8d9f9d-f6f4-41c4-8e4d-d2593a85b94f)



## Data Modelling 


Using fastai's vision learner and restnet34 model my model have achieved accuracy over 80%.Confusion matrix is given bellow.

![image](https://github.com/marufc36/Cat_Classifier/assets/151602012/59089e42-c801-48df-b2a1-45a579169c5e)



```bash
https://colab.research.google.com/drive/1Oe52UDJEzPfvNyTb0TfXdk9YlMGoxHgW?usp=sharing
```

## HuggingFace Deployment 

This model deployed into HuggingFace Spaces. Link is given bellow.

```bash
https://huggingface.co/spaces/mmchowdhury/CatClassifier
```

![image](https://github.com/marufc36/Cat_Classifier/assets/151602012/25adbcb3-043f-41f5-8826-6f12457a2394)







  


