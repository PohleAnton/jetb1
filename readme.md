# Prompt Engineering Project

This repository contains a prompt engineering project I created as part of my studies.

## What Did I Do?

During a class last year, I was tasked with working on a project involving a large language model (LLM). Early in the semester, my teacher introduced some current ideas in the LLM space, including this fascinating paper:  
[Reflections: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2304.03442).

Without diving too deep into the details, the paper describes a crude simulation of a human community. Inspired by this, I set out to create a project where two agents discuss the **simulation hypothesis**. The goal? To have the agents attempt to convince each other whether or not they live in a simulation, and then have them act accordingly as a civilization.

I’d be VERY happy to discuss this in a lot more detail – but since this is supposed to be a technical documentation, I'll keep it short.


---

## Key Features
- **Interactive Agent Simulation**: Two agents debate and explore the simulation hypothesis.
- **Behavioral Adaptation**: Based on their conclusions, the agents act as a "civilization."
- **Streamlit Interface**: A user-friendly interface for exploring the results.

---

## Setup Instructions

Since some dependencies are deprecated, I’ve included a `requirements.txt` and applied crude fixes to ensure the code works with current setups.

### Prerequisites
- **Python Version**: The project is confirmed to work on Python 3.10, but it might also work on versions 3.8 or 3.12.
- **API Key**: You need to provide an OpenAI API key. Add it to `config.yml` before running the code.

### Installation
1. Clone the repository:
   git clone https://github.com/PohleAnton/jetb1.git
   cd prompt-engineering-project

2. Install dependencies:
   pip install -r requirements.txt

3. Configure your OpenAI API key by adding it to config.yml.

### How to run
1. Start the main process:
    chroma run
2. Give it a moment
3. Open a second terminal and launch the Streamlit interface:
   streamlit run DetailBot.py

4. Wait for the system to initialize, open the link displayed in the terminal