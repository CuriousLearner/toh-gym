# toh-gym
Open AI Gym discrete environment for Tower of Hanoi problem

The latest version can be installed using pip:
`
pip install -e git+git://github.com/AlexMatthers/toh-gym#egg=toh-gym
`


## Steps to use -
1. Import the environment using `from toh_gym.envs import TohEnv`
2. Create the environment using `env = TohEnv(poles=3, rings=5, noise=0.1)`
