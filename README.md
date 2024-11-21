# ESP3201-GRP6

## Requirements:
'''
python3
numpy
gymnasium
mujoco
'''

## Running:
The main file to run the env is SB3.py:
'''
usage: SB3.py [algorithm {PPO, SAC, A2C}] [-t {train} or -s{test}] 
[./models/filename {for testing only}]
'''

Example:
'''
python SB3.py PPO -t
'''
'''
python SB3.py PPO -s ./models/PPO_100000.zip
'''
