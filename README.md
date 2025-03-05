# RL_assignment_1

## Problem 1
For Jack's car problem, we implemented the solution within the same file in a new function called `expected_reward_new`. We also modified the functions for policy optimization to receive a reward function so you can change between the two. To run the code with either function, you should go to the main loop and change the function passed to the policy evaluation and policy improvement functions. The results of both runs can be seen in the plots below. You can see that the non-linearities in the new reward function change the optimal policy, such that now there are times where before you would move cars from one location to another in the previous scenario and now you don't. This can be seen in the upper-right corner of the new policy. Furthermore, exchanges from A to B are still being favored as the other location often needs more cars, and moving them from A to B is cheaper.

### Results
#### New Reward Function
![Final Policy with New Reward](final_policy_new_rew.svg)

#### Original Reward Function
![Final Policy with Original Reward](final_policy_original_rew.svg)

## Problem 2

