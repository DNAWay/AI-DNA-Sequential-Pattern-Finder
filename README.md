AI DNA Sequential Pattern Finder

This repository implements an AI-driven pipeline for processing raw DNA sequences and detecting sequential patterns (motifs or regions of interest) using deep learning. It includes data preprocessing, model training, inference, and a CLI tool.

Features

Data Preprocessing: Convert FASTA/FASTQ input into one-hot encoded tensors.

Model Architecture: A configurable Transformer-based model for sequence feature extraction.

Training Script: Train on labeled sequence data to learn pattern recognition.

Inference Utility: Scan new sequences for predicted motifs or regions.

CLI Interface: Simple command-line commands for preprocessing, training, and inference.

├── data/                        # Input sequence files (FASTA/FASTQ)
│   └── example.fasta
├── models/                      # Trained model checkpoints
│   └── transformer_seq_model   
├── outputs/                     # Inference outputs and logs
├── ai_dna_processor.py         # Main Python module with preprocessing, model, inference
├── train.py                     # Training entry point
├── predict.py                   # Inference entry point
├── requirements.txt             # Python dependencies
└── README.md                    # This file
