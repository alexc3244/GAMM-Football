# GAMM-Football



\# Aim of this work is to showcase work of a generalised additive mixed model on real world football data



\## Dataset

\### 23-24 premier league football data

\### response variable : goal difference (home team goals - away team goals), whilst continuous but with discrete levels it was modelled as pure continuous. no constraints or zero inflations, fairly gaussian distribution. 

\### Repeated measure (hence need for a mixed model): home team. using a random intercept as different teams will have different baselines but interested in generalised relationships between inputs and outputs

\#### using a random effects structure for this as it allows generalisation of results to other teams promoted 

\### predictors  - for the continuous inputs they were supplied per home team and away team, theyre we totalled for simplicity in minimising predictors but keep information in model as rich as possible

\#### continuous predictors: corners, fouls, cards, bookie odds (see EDA readme for details), shots

\#### categorical predictors: final results (home, away , draw), day of week, month of year 



\# methodology



\# folder structure



\# dependencies

\## Python 

\### pandas, numpy, seaborn, matplotlib, scikit-learn

\## R

\### mgcv

