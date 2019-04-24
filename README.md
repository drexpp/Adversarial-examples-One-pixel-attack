# Adversarial examples - One pixel attack
Repository for the B.Sc. thesis about adversarial examples in particular One pixel attack, this attack was proposed in [2018 by Jiawei Su et al.](https://arxiv.org/pdf/1712.02494.pdf)

---

## How to try the jupyter notebook

### Downloading precompiled .h5 files

- First of all we need to create the folder structure and download needed files for the project.

  - Inside your root directory which contains the **.ipynb file** create a folder structure as **Data/Saves**, inside Saves introduce the next three files.
    - [Model (10.5 MB)](https://mega.nz/#!ewsE0YRZ!KXcJi29ArGTAgIDtuLjEfJgwg3iXQtlBVckyNIIKxaE)
    - [Training data (1.01 GB)](https://mega.nz/#!u9tyBCZD!Z8a8BHeyxHPQbbDTy_yltg09I0n23nfE4yZ7TQZFdyw)
    - [Test data (666.1 MB)](https://mega.nz/#!2hlmHKBB!tCOMT3f2IGdGb0SraHn7IszUZ6zrevL9dI6A0cl79gE)
- Execute **requirements.txt** as `pip install -r requirements.txt`
- Launch jupyter `jupyter notebook` or `jupyter notebook Traffic-signals-cnn.ipynb`
  
### Downloading images and training a new 

  - Inside your root directory which contains the **.ipynb file** create a folder structure as **Data/Dataset/Training** and **Data/Dataset/Test**
  
  - Download dataset files
    - [Temporarily unavailable](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset)
