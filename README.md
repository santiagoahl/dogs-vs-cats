
<h1 align="center">
  <br>
  <a href="https://www.kaggle.com/c/dogs-vs-cats"><img src="https://storage.googleapis.com/kaggle-competitions/kaggle/3362/media/woof_meow.jpg" alt="Dogs vs Cats" width="300"></a>
  <br>
  Dogs vs Cats CNN Classifier
  <br>
</h1>

<h4 align="center">A Keras implementation of Convolutional Neural Networks.</h4>

<p align="center">
  <a href='https://keras.io/' target="_blank"><img alt='keras' src='https://img.shields.io/badge/Keras-100000?style=for-the-badge&logo=keras&logoColor=FFFFFF&labelColor=D10000&color=D10000'/></a> <a href='https://www.tensorflow.org/?hl=es-419' target="_blank"><img alt='tensorflow' src='https://img.shields.io/badge/Tensorflow-100000?style=for-the-badge&logo=tensorflow&logoColor=EC8D1E&labelColor=908B8B&color=E45A27'/></a> <a href='https://www.kaggle.com/' target="_blank"><img alt='kaggle' src='https://img.shields.io/badge/Kaggle-100000?style=for-the-badge&logo=kaggle&logoColor=37BAE8&labelColor=BEFDFF&color=37BAE8'/></a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>

![screenshot](https://editor.analyticsvidhya.com/uploads/999181_BIpRgx5FsEMhr1k2EqBKFg.gif)

## Key Features

* This deep learning model classifies a photo into cat or dog. It's built with a deep convolutional neural network architecture with de Tensor Flow API Keras. Also uses
	- Data Augmentation
	- Pooling
	- Dropout
	- BatchNormalization
	- Regularizers
	- Padding
* We got a **81.8%** of validation accuracy.
* The learning curve shows a small amount of overfit. The graph is the following

![screenshot](https://winter-anchovy-50e.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fa6a61571-e00f-4661-9d9f-cf137b40e234%2Flearning_curve.png?table=block&id=4be1c4ce-9af8-4576-a39c-6ba947233407&spaceId=12eea25e-0790-4a8f-aa1c-b60f93c02da2&width=1240&userId=&cache=v2)

## How To Use

To clone and run this application, you will need A [Kaggle Account](https://www.kaggle.com/account/login?phase=startRegisterTab&returnUrl=%2F). Note: You can avoid the following cloning steps by just downloading the notebook manually.

```bash
# Clone this repository
$ git clone https://github.com/santiagoahl/dogs-vs-cats.git

# Go into the repository
$ cd dogs-vs-cats

# Install Jupyter Notebooks
$ pip install jupyterlab
$jupyter-lab
$pip install notebook

# Run
$jupyter notebook

# Download notebook 

```
Open Kaggle and upload the downloaded notebook. Then run the data import and libraries import cells and finaly load the model by following these steps:
1. Run the first cells (Data Import and Libraries)
2. Run de `model` definition cell (Wich starts with
`model = models.Sequential()`)
3. Add [this Data](https://www.kaggle.com/datasets/santiagoahumadal/best-model) from kaggle notebooks
4. Load the model by running the **last** two cells.
## Credits

This model uses the following open source datasets and packages:

- [Kaggle dogs vs cats dataset](https://www.census.gov/)
- [Keras](https://keras.io/)
- [Tensorflow](https://www.tensorflow.org/?hl=es-419)
- [Pandas](https://pandas.pydata.org/)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)


## License

MIT

---

> Web Site [santiagoal.super.site](https://santiagoal.super.site/) &nbsp;&middot;&nbsp;
> GitHub [@santiagoahl](https://github.com/santiagoahl) &nbsp;&middot;&nbsp;
> Twitter [@sahumadaloz](https://twitter.com/sahumadaloz)
