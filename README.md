# DataFest-UofT-2022
This repo is for my award-winning group project of [DataFest@UofT 2022](https://www.statistics.utoronto.ca/news/u-t-students-go-win-data-competition-interactive-video-game-risk-youth). The event is an international data analysis and statistics competition, sponsored by the American Statistical Association (ASA). At the event, 25 undergraduate student teams competed to analyze data on the play2PREVENT game. The video game focuses on gaining insight into adolescent behavior and identifying at-risk youth.

Our goal of the project is to investigate the engagement level of participants so that they can learn more and complete more events. Our research question is to understand the probability of completion the game from a survival analysis perspective. You may find our final products in our write-up and the final presentation (.pdf).

Our project has been awarded as the Best Statistical Analysis Award. I was the group leader who designed survival framework for the entire project. The attached JupyterHub Notebook contains the codes to clean the original data (not publicly available) and construct our survival Cox Proportional-hazards Model. Specifically, we fitted a Cox Proportional-hazards Model to provide estimates of the effects of the covariates on the probability of the event completion. The model measures the association between the playing time of participants and whether the event is complete. We obtained Hazard Ratio (HR), the proportion of the completion rate among groups. Our results show that the previous points at this level of the game, age, player's current skill level have significant positive effects on event completions. This part of our group project was done on Python. 