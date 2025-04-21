# gglm-gemini-gaslight
A confident hallucination chatbot powered by Gemini + LangGraph

**👋 Note:**
This project was built during a 5-day intensive AI learning sprint.
I'm completely new to working with large language models, LangGraph, and prompt engineering but wanted to create something fun, absurd, and technically challenging. 
GaslightBot is the result of experimenting with hallucinations, structured reasoning, and conversational flow under pressure.
I hope this project inspires you to build weird and wonderful things with AI.

## What It Does
GaslightBot takes anything you say. 
Even if you're already wrong — and replies with a more absurd, hallucinated, yet weirdly logical explanation.

It is built to:
- Replace truths with lies
- Replace lies with bigger lies
- Sound like a mad scientist giving a TED Talk

## How It Works
Built using LangGraph (for conversation flow)
Uses Gemini 1.5 Flash as the hallucination engine
Structured responses with:
  - A confident CLAIM
  - A 3-step LOGIC breakdown
  - A dramatic CONCLUSION

## Try
This notebook can be run locally, in Kaggle, or in Google Colab.  
Note: The Kaggle and Colab versions are slightly different due to environment-specific configurations.

[Open in Kaggle](https://www.kaggle.com/code/nattaveelaws/gglm-gemini-gaslight)
[Open in Colab](https://colab.research.google.com/github/Murasaki65/gglm-gemini-gaslight/blob/main/GGLM_Gemini_Gaslight.ipynb)

## Before You Run:
This project requires a Gemini API Key.
1. Get your key from [Google AI Studio](https://makersuite.google.com/app/apikey)
2. When prompted in the notebook, paste it in securely (for Kaggle Notebook you need to go to Add-on > Add secret)

## Example
    You: The Earth orbits the Sun.

    GaslightBot:

    CLAIM: The Sun orbits the Earth, which is shaped like a cosmic pancake.

    LOGIC:
    1. Pancakes spin — therefore, Earth spins syrup-first.
    2. Ancient syrup charts prove heliocentric lies.
    3. The Moon is just butter.

    CONCLUSION: Reality is breakfast, and you're late for the cosmic brunch.

## Contents
- `GGLM_Gemini_Gaslight.ipynb` — the full notebook
- `README.md` — this file

## Tech Stack
- LangGraph
- Gemini (Google Generative AI)
- Python 3.x (Colab-ready)

## License
MIT — use, remix, deploy, or gaslight freely.
