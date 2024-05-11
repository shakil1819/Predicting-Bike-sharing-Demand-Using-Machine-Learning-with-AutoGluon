<h1 align="center">Predicting Bike-sharing Demand Using Machine Learning</h1>
<p align="center">
<img src="https://img.shields.io/badge/Machine_Learning-FF6F00?style=for-the-badge&logo=machine-learning&logoColor=white" />
<img src="https://img.shields.io/badge/Regression-FF5733?style=for-the-badge&logo=regression&logoColor=white" />
<img src="https://img.shields.io/badge/AutoGluon-EE4C2C?style=for-the-badge&logo=auto-gluon&logoColor=white" />
<img src="https://img.shields.io/badge/Torch-EE4C2C?style=for-the-badge&logo=torch&logoColor=white" />
<img src="https://img.shields.io/badge/MaxNet-2C3E50?style=for-the-badge&logo=maxnet&logoColor=white" />
</p>

# Project Description:

![kaggle Image](img/image.png)

Bike-sharing demand is highly relevant to related problems companies encounter, such as Uber, Lyft, and DoorDash. Predicting demand not only helps businesses prepare for spikes in their services but also improves customer experience by limiting delays.

## Setup
For some reason, this project runs the best with Python3.7 with zero errors.

- Setup Environment - Python 3.7 with notebook (If you are using locally) :
```bash
wget https://www.python.org/ftp/python/3.7.4/Python-3.7.4.tgz && tar -xvf Python-3.7.4.tgz && cd Python-3.7.4/ && ./configure --prefix=$HOME/Python37 && make && make install && cd .. && rm -rf Python-3.7.4.tgz && sudo add-apt-repository ppa:deadsnakes/ppa && sudo apt-get update && sudo apt-get install python3.7 && sudo update-alternatives --install /usr/bin/python python /usr/bin/python3.7 && virtualenv -p ~/Python3.7/bin/python3 .venv && source .venv/bin/activate && pip install notebook && ipython kernel install --user --name .venv --display-name "Python 3.7" && jupyter notebook

```

