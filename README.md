## DVAE_SPP

This is a project done as a part of the course EE782 : Advanced Topics in Machine Learning. The task we solved is to predict the closing prices of a stock for 5 days given the prices from the past 12 days while tackling the stochastic nature of stock prices

We improvised upon the paper DVAE for Handling Stochasticity in Multi Step Stock Prediction by extracting financial features like MACD, RSI, Volatility in addition to OLHC prices and changing the architecture of the Hierarchial VAE model. We also implemented the diffusion model that progressively adds noise to the input and target sequences and used denoising score matching to clean the noisy samples at the end.

Through this project, we showcased the importance of extracting relevant features to solve the task and also used a refined version of HVAE to improve expressiveness of the approximate posterior distributions both of which together, helped to model the stock prices more effectively given the input variables
