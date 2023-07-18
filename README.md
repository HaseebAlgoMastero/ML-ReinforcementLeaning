# Reinforcement Learning Algorithms and Applications
<img src  = "https://raw.githubusercontent.com/HaseebAlgoMastero/ML-ReinforcementLeaning/main/Reinforcement-Learning-in-ML-TV.webp">
<h2>What is Reinforcement Learning?</h2>
Reinforcement Learning is a type of learning methodology in ML along with supervised and unsupervised learning. But, when we compare these three, reinforcement learning is a bit different than the other two. Here, we take the concept of giving rewards for every positive result and make that the base of our algorithm.

For an easier explanation, let’s take the example of a dog.

We can train our dog to perform certain actions, of course, it won’t be an easy task. You would order the dog to do certain actions and for every proper execution, you would give a biscuit as a reward. The dog will remember that if it does a certain action, it would get biscuits. This way it will follow the instructions properly next time.

We can take another example, in this case, a human child.

Kids often make mistakes. Adults try to make sure they learn from it and try not to repeat it again. In this case, we can take the concept of feedbacks. If the parents are strict, they will scold the children for any mistakes. This is a negative type of feedback. The child will remember it as if it does a certain wrong action, the parents will scold the kid.

Then there is positive feedback, where the parent might praise them for doing something right. This type of learning is called enforced learning.

Here, we enforce or try to force a correct action in a certain way.

So, in short, reinforcement learning is the type of learning methodology where we give rewards of feedback to the algorithm to learn from and improve future results.

<h2>#Terminology in reinforcement learning:</h2>

1. <h2>Agent:</h2>
An entity that perceives, understands and interacts with its environment

2. <h2>Environment:</h2>
Reinforcement learning assumes a stochastic environment which means the environment acts randomly.

3. <h2>Action:</h2>
Any decisions an agent makes as to how to interact with its environment

4. <h2>State:</h2>
The result of every action (i.e) how the environment reacts to the agent

5. <h2>Reward:</h2>
The feedback that is returned to the agent from the environment after ever action/decision. It helps the agent assess itself.

6. <h2>Policy:</h2>
The technique that an agent uses to decide on what action to do next.

7. <h2>Value:</h2>
The rewards of an agent’s decisions

<h2>#Difference between Reinforcement learning and Supervised learning:</h2>
Supervised learning is a training approach in which a competent supervisor curates a data set and feeds it to the training algorithm. The supervisor is in charge of gathering this data, which consists of a collection of samples like as photos, textual fragments, or audio recordings, each with a criteria that categorises the sample. A supervised learning algorithm’s primary goal is to extrapolate and generalise, or to generate predictions for cases not included in the training dataset.

RL is a distinct machine learning approach. RL does not need a supervisor or a pre-labeled environment.

<h2>#Difference between Reinforcement learning and Unsupervised learning:</h2>
Because RL does not need supervision, it is vital to distinguish it from unsupervised learning, another model of dee learning. The training data in unsupervised learning is not categorized, and the goal is to discover the underlying pattern in the data. The model can cluster similar instances or predict the distribution function that produced the instances if it is aware of this underlying pattern. The discovery of this underlying pattern does not address the RL challenge of maximising the payoff at the conclusion of a path. The understanding of a concealed pattern in the agent’s knowledge, on the other hand, can accelerate the learning process

<h1>What is the K-Armed Bandit Problem?</h1>
The K-armed bandit (also known as the Multi-Armed Bandit problem) is a simple, yet powerful example of allocation of a limited set of resources over time and under uncertainty. It has been initially studied by Thompson (1933), who suggested a heuristic for navigating the exploration-exploitation dilemma. The problem has also been studied in the fields of computer science, operations research, probability theory, and economics, and is well suited for exploring with the tools of reinforcement learning.

In its basic form, the problem considers a gambler standing in front of a row of K slot machines (also known as one-armed bandits) and trying to conceive a strategy for which machine to play, for how many times, and when to switch machines in order to increase the chances of making a profit. What makes this premise interesting is that each of the bandits dispenses rewards according to a probability distribution, which is specific to the bandit and is initially unknown to the gambler. The optimal strategy, therefore, would involve striking a balance between learning more about the individual probability distributions (exploration) and maximising the profits based on the information acquired so far (exploitation).
