# Music Genre Classification Using CNN and Classical Machine Learning

This project focuses on classifying music into different genres using **MFCC audio features**, **classical machine learning algorithms**, and later a **1D Dilated Convolutional Neural Network (CNN)**.

The project is inspired by the Stanford CS229 project:

> Music Classification through CNN and Classical Algorithms

## Dataset

The project uses the **GTZAN Music Genre Dataset**.

For this implementation, we use 5 genres:

- Blues
- Classical
- Hip-Hop
- Metal
- Pop

Each genre contains 100 audio files, giving a total of:

- **500 audio files**
- **5 genres**
- **100 songs per genre**

The dataset is organized as:

```text
dataset/
└── genres_original/
    ├── blues/
    ├── classical/
    ├── hiphop/
    ├── metal/
    └── pop/
