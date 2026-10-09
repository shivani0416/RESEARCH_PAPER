# Evaluating the Consistency of Machine Unlearning Verification Under Varying Forgetting Conditions

## Overview

This repository contains the research paper and experimental work investigating the consistency of machine unlearning verification under different forgetting conditions.

The study examines how verification outcomes vary with forget-set size and forgetting difficulty using CIFAR-10, a custom ResNet-18 model, and two unlearning methods: GA_FT and SalUn.

## Research Objectives

* Evaluate verification consistency under varying forgetting conditions.
* Compare evidence from multiple verification signals.
* Investigate whether individual verification signals provide consistent conclusions about unlearning outcomes.

## Methodology

Experiments are conducted on CIFAR-10 using four forgetting conditions, three random seeds, and two machine unlearning methods.

The verification signals include:

* Behavioral accuracy
* Membership Inference Attack (MIA)
* Jensen–Shannon (JS) divergence
* Centered Kernel Alignment (CKA)

## Key Finding

The experiments highlight that different verification signals can produce mixed or neutral evidence under varying forgetting conditions, motivating the use of complementary evidence when evaluating machine unlearning.

## Repository Contents

* Research paper
* Experimental kaggle Notebook
* Results and visualizations

## Scope and Limitations

This work provides an empirical analysis of verification behavior. The retrained reference models are comparison references, not ground-truth proof of successful forgetting.

## Author

Shivani Kawade
