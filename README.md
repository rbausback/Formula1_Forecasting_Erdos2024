# Forcasting Outcomes in Formula 1 Racing: A Machine Learning Approach to Predicting Race Results in Motorsports 
## Erdös Institute Data Science Project

**Research Questions:**

- Explanatory Modeling: Which factors from practice sessions during a given Grand Prix have the most significant impact on the subsequent qualifying round results?
- Predictive Modeling: What level of accuracy can be achieved in predicting the qualifying times for each driver in every Grand Prix, and consequently, the race's starting grid? 

**Background:** A Formula 1 Grand Prix typically follows a structured format over a race weekend, spanning three days: Friday, Saturday, and Sunday. Here's a breakdown of the typical structure:
  - Friday
    - Practice Sessions: There are usually two practice sessions on Friday. These sessions allow teams and drivers to familiarize themselves with the track, test setups, and gather data on tire performance and fuel loads. Each practice session typically lasts around 90 minutes.
  - Saturday
    - Final Practice Session: The third practice session usually takes place on Saturday morning. This session provides one last opportunity for teams to fine-tune their setups and strategy ahead of qualifying.
    - Qualifying Session: Qualifying determines the starting grid for the race. It is divided into three parts:
      - Q1: All cars participate in Q1, which lasts around 18 minutes. The slowest cars are eliminated at the end of Q1, typically around six or seven cars.
      - Q2: The remaining cars compete in Q2, which lasts around 15 minutes. Again, the slowest cars are eliminated, leaving the top ten to progress to Q3.
      - Q3: The top ten cars compete for pole position in Q3, which lasts around 12 minutes. The driver with the fastest lap time in Q3 starts the race from pole position.
  - Sunday:
    - Race Day:
      - Warm-Up: Some circuits have a warm-up session on Sunday morning, allowing teams to do final checks on the cars and drivers to get accustomed to the track conditions.
      - Race: The main event, where drivers compete for points in the Formula 1 World Championship. The race distance is typically around 305 kilometers or a maximum of two hours, whichever comes first. The number of laps varies depending on the circuit's length.

**Data Set:** Our dataset comes from the [official Formula 1 website](https://www.formula1.com). We consider the following variables from each driver across Grand Prix events spanning from 1994 to 2023.
  - number of laps completed in practice
  - fastest lap time and gap to fastest lap in practice
  - qualifying results

**Possible Stakeholders:** 
  - Formula One racing teams and owners
  - Fans
  - Fantasy Formula 1 players

**KPI's:**
  - MSE for the qualifying times across all grand prix
  - cross-entropy for starting grid position probabilities
  - accuracy against true starting position
