# Tech Stack Evaluation

## Project
Smart Leftover Optimizer

## Requirements that drive the decision
List 3 to 5 requirements from your own docs/requirements.md. Include at
least 2 non-functional requirements.
- FR1: The system will permit the user to enter any food item left over, along with its estimated quantity and shelf life in days.  
- FR2: The system will determine whether the entered ingredients violate any safety threshold defined by the pre-LLM food safety rule engine.  
- FR3: The system will formulate the LLM prompt such that leftover ingredients with an expiry period of less than 48 hours get the top priority.   
- NFR1: This process should take no more than 5.0 seconds for the completion of the entire process.
- NFR2: The system should facilitate first-time users to input their leftover food items and obtain a recipe within 3 steps or less.

## Options
- Option A: [for example: static website (HTML and JavaScript) on GitHub Pages]
- Option B: [for example: Python web app (Flask) with a database on a cloud host]
- Option C: [your own idea]

## Decision matrix
Weight: how important the criterion is for YOUR project (1 = low, 5 = high).
Score: how well each option does (1 = poor, 5 = excellent).
Weighted score = weight x score. Add them up for each option.

| Criterion                          | Weight | A score | B score | C score |
|------------------------------------|--------|---------|---------|---------|
| Fits my requirements               |        |         |         |         |
| Skills I already have              |        |         |         |         |
| Time to build before my deadline   |        |         |         |         |
| Free hosting and tools             |        |         |         |         |
| Performance and security needs     |        |         |         |         |
| Room to grow later                 |        |         |         |         |
| **Total (weighted)**               |        |  ****   |  ****   |   ****  |

## Decision record
- **Context:** [what problem, and what limits (time, skills, cost)]
- **Decision:** [the option you chose]
- **Reasons:** [2 to 3 reasons, linked to your requirements and the matrix]
- **Consequences:** [what becomes easy, what becomes hard]
- **Risks and next review:** [what could go wrong, and when you will check again]
