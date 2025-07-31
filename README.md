# Development-of-a-Graph-Neural-Network-GNN-Model-for-Adsorption-Energy-Prediction
This project is done as a part of Molecular Data Science and Materials Informatics course

Introduction
In the realm of computational chemistry, Graph Neural Networks (GNNs) have emerged as
powerful tools for efficiently predicting various molecular properties, particularly for systems
involving the adsorption of organic molecules on metal surfaces. This report details the
development of a GNN model designed for estimating adsorption energies, informed by the
principles outlined in the study titled "Adsorption Energy of Organic Molecules on Metals
GNN". The primary aim is to compare our model's performance against established
benchmarks and derive insights for further optimization.

Background
The existing literature illustrates the efficacy of GNNs, especially the GAME-Net model, in
predicting adsorption energies with accuracy rivaling traditional density functional theory
(DFT) methods. Our project builds upon these methodologies, employing a similar GNN
framework but tailored to address a variety of chemical families, specifically plastics,
biomass, and polyurethanes.

Project Objective
This project seeks to implement a Graph Neural Network (GNN) in PyTorch Geometric
to forecast adsorption energies from molecular graph representations learned from the FG
dataset. The performance of the model is evaluated using typical regression metrics—MAE,
RMSE, and R²—and compared to the state-of-the-art GAME-Net architecture in the
reference study.

Dataset
BM Dataset: The big molecules dataset (BM dataset) consists of a diverse array of organic
compounds that include plastics, biomass, and polyurethanes. This dataset was essential for
evaluating the model's performance across different chemical families.
Data Characteristics: The dataset includes 3,315 samples derived from DFT calculations,
ensuring a robust training source with representations that reflect real-world scenarios in
adsorption phenomena.

