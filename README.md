# Traffic station classification for Traffic Management

<img width="937" alt="Screenshot 2021-09-13 at 10 01 47 AM" src="https://user-images.githubusercontent.com/35477453/133013230-63bdbe32-3a45-4e19-b635-f7e9ab91a006.png">


## Overview 

Traffic management is a critical concern for policymakers. With the publicly available [US Traffic 2015 dataset](https://www.kaggle.com/jboysen/us-traffic-2015) compiled by the US Department of Transportation, we will conduct an in-depth analysis to help the department understand which areas in the United States have high traffic volume, what factors are associated with high traffic volume and if there are any things policy-wise we can do to improve traffic management for these areas.

More details can be found in traffic-station-classification.ipynb.

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
    
  
