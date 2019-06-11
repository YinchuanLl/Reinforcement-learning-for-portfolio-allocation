# reinforcement-learning-for-portfolio-allocation
Optimistic Bull or Pessimistic Bear: Adaptive Deep Reinforcement Learning for Stock Portfolio Allocation

If you feel that our code is helpful to you, please cite our paper:

Xinyi Li, Yinchuan Li, Yuanchen Zhan, Xiao-Yang Liu, "Optimistic Bull or Pessimistic Bear: Adaptive Deep Reinforcement Learning for Stock Portfolio Allocation," International Conference on Machine Learning (ICML) Workshop on AI in Finance, May 2019.

Please follow the instructions below to run the code:

### Prerequisites 
Python 3.6 envrionment 

Anaconda3

Tensorflow

#### OpenMPI
Installation of system packages OpenMPI 

#### Install gym under tensorflow
pip install gym

### Download Official Baseline Package and install it 
 git clone https://github.com/openai/baselines.git
 cd baselines
 pip install -e .
    ```
### Find the following files and change the address in the files into your address
./gym/envs/__init__.py 
./gym/envs/portfolio/ portfolio_env.py
./gym/envs/portfolio/ portfolio_testenv.py

#### Baseline
- Find your baselines folder, and replace it with baseline in this repository

#### Gym
- Find your gym folder, and replace it with gym in this repository

### Code description
./baselines/baselines/run.py used for train or test 
./baselines/baselines/common/cmd_util.py used for parameter configuration
./baselines/calculate_table.py used for generating data for Table 1 in paper 
./baselines/plot_financial.py used for generating figure for Figure1 in paper
./baselines/plot_property.py used for generating figure for Figure 5 and Figure 6 in paper
