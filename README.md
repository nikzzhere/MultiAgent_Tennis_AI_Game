# MultiAgent_Tennis_AI_Game
Deep Deterministic Policy Gradient (DDPG) Algorithm for Tennis Unity ML-Agent Environment
State Space:
The observation space consists of 8 variables representing the position and velocity of the ball and racket. Each agent receives its own local observation.
Action Space:
The action space is continuous, with 2 continuous actions available for each agent, corresponding to movement toward (or away from) the net and jumping.
Solution Criteria
The environment is considered solved when both agents achieve an average score of +0.5 over 100 episodes.
Installation Instructions
1) Setting Up Python Environment:
a) Download and install Anaconda 3 (latest version 5.3) for the specific operating system and architecture (64-bit or 32-bit) being used for Python 3.6 and newer.
b) Create and activate a new environment with Python 3.6 using the following commands: - Linux or Mac:
conda create --name drlnd python=3.6 source activate drlnd - Windows:
conda create --name drlnd python=3.6 activate drlnd
c) Minimal Installation of OpenAI Gym Environment:
git clone https://github.com/openai/gym.git
cd gym pip install -e . Alternatively, install the packaged version directly from PyPI: pip install gym d) Clone the repository (https://github.com/udacity/deep-reinforcement-learning.git) and navigate to the python/ folder. Install dependencies:
git clone https://github.com/udacity/deep-reinforcement-learning.git cd deep-reinforcement-learning/python pip install.
2) Install Unity ML-Agents:
a) Clone the Github Repository (https://github.com/Unity-Technologies/ml-agents.git) and install the required libraries by running the following commands in the Anaconda Prompt:
git clone https://github.com/Unity-Technologies/ml-agents.git cd ml-agents/ml-agents pip install .
3) Download the Unity Environment:
a) Download the pre-built Unity environment from the following links based on the operating system:
- Linux
- Mac OSX
- Windows (32-bit)
- Windows (64-bit)
b) Place the downloaded file in the p3_collab-compet/ and python/ folders in the DRLND GitHub repository, then unzip the file.
c) For Windows users, determine the system architecture using this link.
Running the Code
Place source code files and pretrained model weights in this cloned GitHub Repo inside the python/ folder of the Deep-RL cloned repository folder.
Place the folder containing the downloaded Unity environment file for Windows (64-bit) OS inside the python/ folder of the Deep-RL cloned repository folder.
Open Anaconda prompt shell window and navigate inside the python/ folder in the Deep-RL cloned repository folder.
Run the command jupyter notebook from the Anaconda prompt shell window to open the Jupyter notebook web-app tool in the browser.
Before running code in a notebook, change the kernel (IPython Kernel created for drlnd environment) using the drop-down Kernel menu.
The source code present in the provided training and testing notebooks (.ipynb files) can also be collated in respective new Python files (.py files) and then executed directly from the Anaconda prompt shell window
