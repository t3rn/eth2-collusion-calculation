# Ethereum Sync Committee: Probability of Collusion in Voting Scenarios
This repository contains a Jupyter notebook that calculates and visualizes the probability of a wrong decision being made in the Ethereum Sync Committee voting scenario, given different thresholds of accepted majority share and varying levels of dishonest participants.

## Features
Calculation and visualization of collusion probabilities within the Ethereum Sync Committee using the cumulative binomial distribution.
Presentation of probabilities in an easy-to-understand table format.
Highlighting specific points on the plot for a better understanding of key values.
Allows flexibility in terms of number of participants (i.e., validators), accepted majority share values, and specific marker points.
## Getting Started
To run the notebook, you will need to have Python installed, along with the libraries numpy, scipy, matplotlib, and pandas.

## Usage
The Jupyter notebook is split into two main sections:

**Probability of Collusion:** This script generates a series of plots for each specified accepted majority share in the Ethereum Sync Committee. On each plot, the x-axis represents the probability of a validator acting dishonestly, and the y-axis represents the corresponding probability of the collective decision being wrong.

**Probability Chart:** This script calculates and presents the probabilities of an incorrect decision in a table format, for varying levels of validator dishonesty and different accepted majority thresholds in the Ethereum Sync Committee. Each cell in the table represents the probability of an incorrect decision for a specific combination of dishonesty probability and accepted majority threshold.

You can adjust the total number of validators (n), the accepted majority values, and specific marker points according to your needs.

**Contributing**
If you wish to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

**License**
The code in this project is licensed under MIT license.
