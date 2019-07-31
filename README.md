# A Jupyter Notebook Exploring and Educating on Basic ML Via Keras & Mnist 

As the title suggests. This is a jupyter notebook that utilizes the tensorflow Keras library to explore the mnist dataset. This notebook has a focus on exploration and education as opposed to high accuracy. It is meant to be useful as a way to explore the ease in which Keras can create models, as well as how to visualize predictions and raw data.

## Getting Started

```
1. Clone this repository
2. Create an environment (and activate it) and install the requirements.txt file
3. Launch jupyter
4. Open the file from the cloned repositry
5. Enjoy
```

## Prerequisites

```
cycler==0.10.0
h5py==2.9.0
Keras==2.2.4
Keras-Applications==1.0.8
Keras-Preprocessing==1.1.0
kiwisolver==1.1.0
matplotlib==3.1.1
numpy==1.17.0
opencv-contrib-python-headless==4.1.0.25
pyparsing==2.4.2
python-dateutil==2.8.0
PyYAML==5.1.1
scipy==1.3.0
six==1.12.0
```

## Installation
**NOTE: all shell commands are via the windows command line... you can find alternatives for linux fairly easily**

1. Clone this repository and navigate into it within the command line

2. Create and activate an environment (if you wish)<br>
` python -m venv env `<br>
` env\scripts\activate `<br>
` python -m pip install --upgrade pip `<br>

3. Execute the following commands to install all the requiremets<br>
` pip install -r requirements.txt`<br>

4. To open the jupyter environment run the following<br>
` jupyter notebook --port=8888`<br>

5. Navigate to the cloned directory and open the .ipynb file<br><br>
***See deployment for notes on how to deploy the project on a live system.***

## Deployment

To deploy this on a system and leave it running, you will need to attach the jupyter instance to a seperate 'screen' in the terminal/cmd prompt. There are different ways of doing this but you should be able to find the appropriate documentation easily. <br>
As this is a learning tool, there is no further information regarding deployment via docker, etc.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests.

## Authors

**Darien Schettler** -- [Portfolio](http://darienschettler.ca/) -- [Github](https://github.com/darien-schettler)


## Licensing

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
