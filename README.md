### About me

- Name: Zhihan
- Pronouns: he/him/his
- Major: Mathematics
- Affiliation: Carleton College (in Minnesota)
- Email: yangz2@carleton.edu
- Research interests: machine learning theory, Python, PyTorch, deep reinforcement learning

### Tips on debugging machine learning code (and anecdotes)

- Do a lot of shape checking (use print statements or debugger) to prevent incorrect broadcasting.
  - In PyTorch, if you add a (64, ) and a (64, 1) tensor, you get a (64, 64) tensor. 
- Find a working repository and try to mold it into your code - then you can tell the differences. 
- Ask someone else to look at it.

### Good resources on reinforcement learning

- [OpenAI Spinning Up](https://spinningup.openai.com/en/latest/index.html)
  - They have the clearest explanation of DDPG; it was much easier to read than the original paper.
- Think you can't use Mujoco? Well, think twice. Mujoco offers free student / 30-day trial licenses [here](https://www.roboti.us/license.html).
