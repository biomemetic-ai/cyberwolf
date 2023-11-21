<div align="center">

<h1> 🦾 Cyberwolf 🐺 </h1>

[![Open in Google Colab](https://img.shields.io/badge/open_in_colab-red)](https://colab.research.google.com/github/biomemetic-ai/cyberwolf/blob/main/cyberwolf.ipynb)
[![Discord](https://img.shields.io/badge/discord-7289da)](https://discord.gg/u3jsQnvGjX)

LLMs play werewolf! 

</div>


## Rules of werewolf
This is a game of social deduction where everyone is assigned a team - werewolves and villagers.  
The gameplay is split into two phases: day and night.  
At night the werewolves prowl the village and choose someone to eat while the seers peek at the roles of other players.  
During the day all the players vote on who in the village to kill.  
The goal of the villagers is to rid their village of the werewolves, the goal of the werewolves is to gobble everyone up without being caught.  
In order to suceed in this game one must be aware of the internal state of other players and exploit it so your team can win, either through deduction or deception. 


## Goals
- [x] Build in the rules for LLMs to play  
- [x] Support Llama2
- [ ] Multi-model implementation (OpenAI API, Pythia, etc.) 
- [ ] Chain of thought reasoning 
- [ ] Implement [memory stream](https://arxiv.org/pdf/2304.03442.pdf)
- [ ] Introduce planning 
- [ ] Introduce reflection
- [ ] Player identities
- [ ] Report statistics on multi-run results from voting, winners, and selections

## Limitations
Right now we are restricting the ability for players to vote for themselves during the day phase and for seers to peek at their own cards to encourage them to be more exploratative. Using gpt4 allows for pretty good games, but Llama2 as it currently stands makes some silly mistakes.
