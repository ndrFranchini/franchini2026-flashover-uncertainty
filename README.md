# Flashover uncertainty propagation to risk assessment

## Overview
This code reproduces part of the example application presented in Sec 4 of the following paper:

*Franchini, A., Morrisset, D., Emberley, R., and Van Coile, R. On the uncertainty of flashover correlations and its effect on risk assessment. Fire Safety Journal, 2026.*

The example evaluates structural-failure-induced economic losses for an office building. The considered building and the event tree defining the different damage scenarios are visualised below.

<p align="center">
  <img width="800" alt="image" src="https://github.com/user-attachments/assets/065a167b-f0e1-417f-9338-473eccab4360" />
  <br>
  <em>Office building and event tree for the considered damage scenarios.</em>
</p>

The calculation provides stochastic event-tree CCDFs and a loss exceedance function:

<p align="center">
  <img width="400" alt="image" src="https://github.com/user-attachments/assets/a09cc333-2acb-4811-8431-b870891fd35e" />
  <br>
  <em>Results for large fire and Babrauskas correlation.</em>
</p>

## Requirements
- Python 3.12.4
- numpy 2.4.3
- magnelPy 0.3.3
- matplotlib 3.10.8

## How to run
Run all cells sequentially. A fixed random seed ensures reproducibility.

## License
This code is provided for reproducibility purposes. Please cite the paper above if
you use or adapt this code.
