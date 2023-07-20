# Modeling the Transmission of SARS-COV-2 (COVID-19) in a NetLogo Environment 😷
### Project Socially Aware Computing @ Vrije Universiteit Amsterdam 🎓

A work of Mark Bartos made for the Year 2 class of Project Socially Aware Computing.

## About the Research Paper 📑

**Goal**
Simulate COVID-19 transmission and investigate how early application of preventative measures (mask-wearing, staying at home, vaccination) impacts the virus spread.

**Research Question**
How does the combination of different strategies and their early applicability impact the spread of the SARS-CoV-2 virus in a simulated population?

**Experiments**
The model will be run 40 times with different combinations of prevention strategies. Results will be analyzed to determine the most effective measures.

**Conclusion**
Combining preventative strategies is the most effective way to slow down the spread of COVID-19. Future work could explore multiple waves of infections and the impact of delayed measures.

## About the Code-base and the Modell 🧑‍💻

*💡 The code-base and research paper is made avaliable for grading purposes.*

This NetLogo simulation model studies COVID-19 spread and prevention strategies. It tracks a population of turtles representing individuals, their infection status, and immunity.

**Global Variables:**

- **countNonInfected**: Count of non-infected turtles.
- **countInfected**: Count of infected turtles.
- **countImmune**: Count of immune turtles.

**Procedures and Functions:**

- **setup**: Initializes the simulation with infected and non-infected turtles.
- **go**: Main simulation loop that handles infection, recovery, and movement of turtles.
- **infect**: Handles turtle infection based on policies (mask and vaccination).
- **recover**: Manages turtle recovery process.
- **percNonInfected**, **percInfected**, and **percImmune**: Report the percentage of non-infected, infected, and immune turtles.

**Simulation Behavior:**

- Runs until no infected turtles remain.
- Turtles move randomly with different distances depending on quarantine policy.
- Infection depends on vaccination and mask policies.

**Data Collection:**

- Tracks percentages of non-infected, infected, and immune turtles over time.

## Results 📊
⚫️ Black line: Non-Infected

🔴 Red line: Infected

🟢 Green line: Recovered

![Results](https://github.com/mrkbrts/vu-psac/blob/b58bcb8bca8ed3bb921d57f4c2c4040e11b97116/Result%20overview.png)

