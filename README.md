# Machine-Learning-Tutorial
In this repository i store my lab exercise of Human Data Analytics course.
The tutorial provided by the lecturer are simple and very well described.
Of course for every topic, some background are needed, that's why i will try
to attach more information in order to make the exercise more understandable.

## Getting Started
Let's start from setting-up the environment.
The following instructions are thought to be platform indipendent.

The Labs are essentially based on python3 and its "graphical frontend" [Jupiter](http://jupyter.org/).. 

Python has an internal packets/modules installer named pip so the required software is made by the following parts:

Packages:

* python3 <br/>
* python3-pip <br/>
* python3-pandas  <br/>

Modules for pip: (generally, first of all, you should upgrade pip) <br/>
* jupyter <br/>
* h5py <br/>
* scikit-image <br/>
* keras (version 2.0.7) <br/>
* tensorflow (version 1.2.1) <br/>
* pydot <br/>

EXAMPLE (LINUX ONLY) <br/>
Linux users have an easy life (root shell or sudo commands):<br/>

```
apt-get install python3 python3-pip python3-pandas
python3 -m pip install --upgrade pip
python3 -m pip install jupyter h5py scikit-image keras==2.0.7 tensorflow==1.2.1 pydot
```

OTHERS PLATFORM :) <br/>
Equivalent steps should be done with other operating system according to their internal organization (library managament, installers, etc).

### Get your hand dirty
Once you have completed and follow the instruction above,go to the repo folder and load the first tutorial:
```
~/Machine-Learning-Tutorial/1 - B_Numpy$ jupyter notebook PythonNumpy.ipynb
```
##Tutorials

### 1- Basic Numpy
A good start with some basic concept like:
* computation of a sigmoid function
* computation of a loss function
* deal with different dimension and broadcasting
* Reshaping Arrays
* Sigmoid descent

