# Music Genre Classification Using CNN and Classical Machine Learning

## Team Members

| Name | SRN |
|---|---|
| R. Pooja | PES2UG24CS388 |
| R G Nithik | PES2UG24CS386 |

---

## Project Overview

This project focuses on **music genre classification** using audio features and machine learning techniques.

The project uses **MFCC (Mel-Frequency Cepstral Coefficients)** as the primary audio feature representation and compares classical machine learning algorithms with a **1D Dilated Convolutional Neural Network (CNN)**.

The project is based on the Stanford CS229 project:

**"Music Classification through CNN and Classical Algorithms"**

---

## Dataset

The project uses the **GTZAN Music Genre Dataset**.

For this implementation, five music genres are considered:

- Blues
- Classical
- Hip-Hop
- Metal
- Pop

Each genre contains 100 audio files, resulting in:

- **5 genres**
- **100 songs per genre**
- **500 songs in total**

### Dataset Structure

```text
dataset/
└── genres_original/
    ├── blues/
    ├── classical/
    ├── hiphop/
    ├── metal/
    └── pop/
