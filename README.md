# Reinforcement-Learning---Continuous-Control
DDPG algorithm applied to a continuous control problem
# Reinforcement Learning - Actor Critic Method - Deep Deterministic Policy Gradient

Deep Deterministic Polict Gradient Actor-Critic Method is applied to solve continuous control problem. Agent is trained to follow a conituously changing target.

## Environment Details
This is a robotic arm environment. 

To be completed



## Setup

- **Clone the DRLND Repository**
    
    Follow the instructions in the DRLND GitHub repository [click here](http://github.com/udacity/deep-reinforcement-learning#dependencies)
    

- **Download the enviroment**
  
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
   
   (_For Windows users_) Check out 
    [click here](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version     or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not 
    [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use 
    [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.
    
  - **Place Environment file in DRLND repository**  
    
      Place the downloaded file from the previous step in the DRLND GitHub repository, in the `p3_collab-compet/` folder, and           unzip (or decompress) the file. 

- **Clone this repository**
    
    Clone this repository in the DRLND GitHub repository
    
 ## Usage and structure
 
    - To train the agent run 'Continuous Control_Solution.ipynb' file. 
    
    - 'ddpg_agent.py' - Interacts with and learns from the environment. Parameters can be modified in this file.
    
    - 'Model.py' is the policy model. Neural network architecture is defined here.
