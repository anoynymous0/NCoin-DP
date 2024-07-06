# Nerual Conformal Inference for Jump Diffusion Processes (NCoin-JDP)
## 1. Tutorial
We first provide a tutorial for NCoin-DP. It contains

- How to generate synthetic data (Sec 2.1)
- Functions of input statistic (Sec 2.2)
- Learning the mapping using DNN (Sec 2.3)
- Learning checking procedure (Sec 2.4)
- Uncertainty characterization (Sec 3)

using OU process. For detailed, go to `OU_tutorial.ipynb` above.


## 2. Simulation
### Section 5.1
In this section, we consider OU process to evaluate the performance of NCoin-DP. We provide codes for simulation and numerical results for NCoin-JDP, MLE, GMM, and MCMC. The NCoin-JDP, and MLE methods are implemented through `Python`, and the GMM and MCMC methods through `R`. `Jupyter Notebook`s are provided for `Python` code, and `R` scripts are also provided.

In order to reproduce the results in Section 5.1, first you should generate synthetic data and test data. Go to `simulaiton generator.ipynb` file and implement those. Using the synthetic data, we implement the NCoin-JDP. The test data are evaluated by all of four methods.

For NCoin-JDP, implement `OU_sim.ipynb'. For GMM and MCMC, we implemented and uploaded the results in this directory, so just download the results. The source code is available upon request.

## Section 5.2


## 3. Real Data Analysis
We collect adjusted closing price of MSFT and ADBE on n=1259 trading days between January 01, 2013 and December 31, 2017. See the image below. We model a pair trading schemes using those two data. For detailed analysis go to the folder, `RealDataAnalysis` and run `adbemscf.ipynb`


<img width="779" alt="Screenshot 2023-03-03 121408" src="https://user-images.githubusercontent.com/126707827/222784718-b72d35a1-33b0-44d3-bb47-769b1282e57f.png">
