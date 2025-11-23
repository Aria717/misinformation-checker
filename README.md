# Cornell Fact Checker - Model Development

This notebook contains the fact-checking model I developed for the Cornell Fact Checker project using sentence-transformers and semantic similarity.

## Overview

The model verifies claims about Cornell-specific information (courses, meal plans, financial aid) by computing semantic similarity between user claims and ground-truth data.

## My Contribution

I developed the core fact-checking logic:
- Implemented semantic similarity matching using sentence-transformers
- Designed the verification pipeline to compare claims against factual data
- Integrated the model with the Flask backend for real-time inference

## Technical Approach

- **Framework**: sentence-transformers, PyTorch
- **Method**: Semantic similarity scoring between claim embeddings and fact embeddings
- **Data**: Cornell-specific datasets (courses, meal plans, financial aid)

## Full Application

This model was part of a collaborative class project. The complete application (Flask backend + Chrome extension) is available at: [https://github.com/jla292/info4125]
