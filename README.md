# Reward Estimation for Variance Reduction in Deep Reinforcement Learning
## Installation

We based our code primarily off of [ikostrikov's pytorch-rl repo](https://github.com/ikostrikov/pytorch-a2c-ppo-acktr). Follow installation instructions there. 

### Make sure to be using pytorch 0.3.1 

## How to run

To replicate the mujoco results (with gaussian noise) from the paper you need to run all 750 runs individually with:

``` python main.py --continuous --use-gaussian-noise --run-index [0-749] ```

To replicate the mujoco results (with uniform noise) from the paper you need to run all 750 runs individually with:

``` python main.py --continuous --use-uniform-noise --run-index [0-749] ```

To replicate the mujoco results (with sparse noise) from the paper you need to run all 750 runs individually with:

``` python main.py --continuous --use-sparse-noise --run-index [0-749] ```

To replicate the atari results (with gaussian noise) from the paper you need to run all 270 runs individually with:

``` python main.py --use-gaussian-noise --run-index [0-269] ```

To replicate the atari results (with uniform noise) from the paper you need to run all 189 runs individually with:

``` python main.py --use-uniform-noise --run-index [0-188] ```

To replicate the atari results (with sparse noise) from the paper you need to run all 189 runs individually with:

``` python main.py --use-sparse-noise --run-index [0-188] ```

## Visualization

run visualize.py to visualize performance (requires Visdom)
