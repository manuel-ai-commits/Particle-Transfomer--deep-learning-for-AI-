**Application of Particle Transformer for Jet Tagging**

The application of machine learning has brought about a groundbreaking shift in the analysis of large-scale data sets within particle physics, substantially amplifying the potential for uncovering new fundamental laws of nature. Particularly, deep learning has revolutionized the process of jet tagging, a crucial classification task conducted at high-energy particle colliders like CERN's LHC, resulting in a remarkable enhancement of its performance. A crucial part about experiments conducted in particles colliders around the world as the Large Hadron Collider in Genève, consists in the so called "Jet Tagging" task.

When two particle beams are run into collision at small fraction below the speed of light, such as two high energy proton beams, they can produce new unstable particles that decay in a spray of outgoing particles, called a Jet. These outgoing particles are measured by complex detector systems, so that these jets can be reconstructed from the measured particles. The goal of jet tagging is to classify the jets and identify those arising from particles of high interest, e.g., the Higgs boson, the W or Z boson, or the top quark.

![68747470733a2f2f692e696d6775722e636f6d2f5a5956477332642e706e67](https://github.com/user-attachments/assets/32ad7131-a70d-4650-bd5f-9e501bd330a5)

The aim of this project is to implement a Transformer classifier architecture to do such a task, a
nd to succesfully train it using the new state of the art dataset in this context: JetClass. 

This work takes inspiration from the paper "Particle Transformer for Jet Tagging" by Huilin Qu, Congqiao Li, Sitian Qianm. Starting from the cited work, a simpler but hopefully performing neural network architecture will be implemented following the Authors' proposal step by step.

![Screenshot 2025-03-19 at 22 32 27](https://github.com/user-attachments/assets/c3a3db70-85da-4a15-84eb-6207e79f86d4)

Original paper: https://arxiv.org/abs/2202.03772
