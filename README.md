# DVAE_SPP

This is a project done as a part of the course EE782 : Advanced Topics in Machine Learning. We improvised upon the paper DVAE for Handling Stochasticity in Multi Step Stock Prediction by extracting financial features like MACD, RSI, Volatility in addition to OLHC prices and changing the architecture of the Hierarchial VAE model. We also implemented the diffusion model that progressively adds noise to the input and target sequences and used denoising score matching to clean the noisy samples at the end.
