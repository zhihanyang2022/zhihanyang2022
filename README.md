### About me

- Name: Zhihan
- Pronouns: he/him/his
- Major: Mathematics
- Affiliation: Carleton College (in Minnesota)
- Email: yangz2@carleton.edu
- Research interests: machine learning theory, Python, PyTorch, deep reinforcement learning

### Favorite quotes for curbing anxiety in modern age

- Everyone should get rich and famous and get everything they dreamed of so they can see that's not the answer - Jim Carrey.
- Pain is inevitable, but suffering is a choice - not me.
- To live a meaningful life (有意义), you should first strive to live an interesting and fun life (有意思) - not me.
- Having meaningful relationships is the number one predictor for a happy life - not me.
- The existence of multiple alternatives makes it easy for us to imagine alternatives that don’t exist—alternatives that combine the attractive features of the ones that do exist. And to the extent that we engage our imaginations in this way, we will be even less satisfied with the alternative we end up choosing. So, once again, a greater variety of choices actually makes us feel worse - Barry Schwartz, The Paradox of Choice: Why More Is Less

I'm just another human being trying to enjoy life in the face of many challenges. If I can do it, then you can do it!

### Tips on debugging machine learning code (and anecdotes)

- Do a lot of shape checking (use print statements or debugger) to prevent incorrect broadcasting.
  - In PyTorch, if you add a (64, ) and a (64, 1) tensor, you get a (64, 64) tensor. 
- Find a working repository and try to mold it into your code - then you can tell the differences. 
- Ask someone else to look at it.

### Good resources on reinforcement learning

- [OpenAI Spinning Up](https://spinningup.openai.com/en/latest/index.html)
  - They have the clearest explanation of DDPG; it was much easier to read than the original paper.
- Think you can't use Mujoco? Well, think twice. Mujoco offers free student / 30-day trial licenses [here](https://www.roboti.us/license.html).
