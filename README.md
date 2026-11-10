# Stress-Testing the Stylometric Pipeline

This repository contains the official replication framework, interactive notebooks, and calibration datasets for the study: **"Stress-Testing the Stylometric Pipeline: A Case of Constructed Structures under Blind Preprocessing."**

## 🎯 Project Overview
This study exposes the mathematical vulnerability of standard unsupervised decomposition workflows (SVD/PCA) against blind feature-scaling operations in authorship attribution. Using Early Modern English dramatic collaborations (Shakespeare vs. Fletcher) as an adversarial testbed, we demonstrate how Z-score standardization constructs stable but spurious pseudo-structures out of lexical noise. We provide a verification framework based on a calibrated functional subspace audit and multiverse specification curve analysis.

## 💻 Repository Structure
* `shakespeare_pipeline_audit.ipynb`: The primary interactive Google Colab notebook containing the pipeline stress-tests, SVD geometries, and the 200-model specification curve loop.

## 🛡️ Reproducible Research Open Data
The static code release is permanently archived on Zenodo under the master concept DOI: `10.5281/zenodo.XXXXX`.

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
