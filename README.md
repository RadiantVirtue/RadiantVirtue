# hey, i'm rhian

i like to build stuff that learns.

final-year **CS & AI** student at the University of Bath. most of my time goes into reinforcement learning - specifically, figuring out what RL agents are *actually* learning under the hood.

## what i'm working on

**dissertation** - building a comparative interpretability framework for credit assignment in deep RL. i'm analysing how PPO and SAC process success and failure at the gradient level, using gradient opposition scoring, coherence analysis, and representational similarity tracking across training. the novel bit is **moment-of-reward analysis**: measuring whether off-policy methods systematically underweight preparatory actions in favour of immediate-reward states. early results suggest they do, and the bias develops late into convergence.

everything - agents, checkpointing, analysis pipeline - built from scratch.

## things i've built

**personalised AI assistant** - fine-tuned a local LLM on personal command patterns, integrated gesture control via hand tracking, facial recognition for guest mode, and custom MCP servers for retrieval. fully offline, runs on consumer hardware. the whole thing is event-driven across voice, gesture, and visual input.

**adaptive workout planner** - formalised my gym routine as an MDP. muscle groups as graph nodes, fatigue as dynamic state, SAC as the policy. trained for 1M steps against a simulated user model. the agent independently discovered a deload threshold at fatigue 7. validated over a 3-month self-experiment - 17% greater progression than my manual programming.

**job matching system** *(in progress)* - LLM-powered pipeline that reasons about implicit job preferences rather than keyword matching. if you say "i don't want to get dirty", it should know warehouse work is a bad fit even when the listing doesn't mention it.

## stack

`python` · `pytorch` · `tensorflow` · `c/c++` · `typescript` · `angular` · `docker` · `linux` · `postgresql` · `firebase`

## what's next

applying for masters programmes in AI/ML - building the formal depth in probabilistic reasoning, bayesian methods, and optimisation i need to push my interpretability work into hierarchical and model-based RL. long-term goal is a PhD in RL interpretability.

i think the gap between what RL agents can do and what we understand about how they do it is widening. i want to build tools that close it.

## find me

[website](https://radiantvirtue.github.io) · [linkedin](https://linkedin.com/in/rhiankansara) · rhiankansara20@gmail.com
