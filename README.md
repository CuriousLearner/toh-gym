# toh-gym

Open AI Gym discrete environment for Tower of Hanoi problem

The latest version can be installed using pip:
`pip install -e git+git://github.com/CuriousLearner/toh-gym#egg=toh-gym`

## Steps to use -

1. Import the environment using `from toh_gym.envs import TohEnv`
2. Create the environment using `env = TohEnv(initial_state=((2, 1, 0), (), ()), goal_state=((), (), (2, 1, 0)), noise=0.1)`
