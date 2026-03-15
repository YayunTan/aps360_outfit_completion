# APS360 Outfit Completion Project

This project builds image-based outfit completion models using DeepFashion.

## Dataset
This project uses the DeepFashion Category and Attribute Prediction Benchmark.

## Models
- Baseline: Frozen ResNet-18 + cosine similarity
- Primary: Fine-tuned ResNet-18 + triplet loss

## Metrics
- Hit@1
- Hit@5
- MRR
