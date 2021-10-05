### This project was completed as part of the Columbia University 2021 Data Science Hackathon
- Competition lasted about 14 hours to complete both code and presentation portions of submission
- Worked as part of a great team, uploaded my specific portions of the project here

### Used the COVID-19 misinformation dataset to create an algorithmic way of determining fake vs. real news claims about COVID-19

### Background Resources
- Data: https://github.com/cuilimeng/CoAID
- Related Paper: https://arxiv.org/abs/2006.00885

### Process
- Discovered 20 recurrent topics within the COVID-19 news claims using the CorEx Topic modeling algorithm
- Used the topics discovered within the claims, along with Twitter interaction of the claims (tweets and replies), as features in a predictive model to determine fake vs. true news claims regarding COVID-19
  - Applied SMOTE oversampling technique on the fake news claims to offset the imbalance between real vs. fake news claims in the dataset

### Future steps
- Apply anchoring in topic modeling process to see if topic derivation can be improved
- Apply additional algorithmic approaches to claim validity determination model to improve model AUC
- Results at time of hackathon submission: 
  - Accuracy: 93.59%
  - AUC: 0.6710
- Apply hyperparamter tuning through GridSeaarch to determine best overall model
- Include additional features in predictive model such as claim source or claim date


