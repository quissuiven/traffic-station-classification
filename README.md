# Traffic station classification for Traffic Management

## Overview 

https://www.kaggle.com/jboysen/us-traffic-2015

## How to use 

1. Clone this repository on your local

  `git clone https://github.com/quissuiven/traffic-station-classification.git `

2. Navigate to  traffic-station-classification folder and install virtual environment
  ```
  cd traffic-station-classification
  pip install virtualenv
  virtualenv venv
  source venv/bin/activate
  ```

3. Download [US Traffic 2015 dataset](https://www.kaggle.com/jboysen/us-traffic-2015) into folder
 
4. Install packages based on requirements.txt

  ```
  pip install -r requirements.txt
  ```
  
5. Install jupyter and add virtual environment as kernel

  ```
  pip install jupyter
  ipython kernel install --name venv --user
  ```
  
6. Start jupyter environment

  ```
  jupyter lab
  ```
7. Select virtual environment venv as kernel and open traffic-station-classification.ipynb
    
  
