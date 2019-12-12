
**Many changes have been done to the NILMTK-API. The code needs to be changed slightly in order to make it run with the API. Refer to the NILMTK-contrib about the latest documentation.**

# Buildsys 2019 Paper Notebooks!

In this repository you can find the notebooks that are associated with the paper results of the [NILMTK's Buildsys 2019 paper]([https://nipunbatra.github.io/papers/batra_buildsys_19.pdf](https://nipunbatra.github.io/papers/batra_buildsys_19.pdf)). The notebooks demonstrate the power of the new API. 

# Experiments
The algorithms used in the paper are as follows

- Mean Algorithm
- Hart's Algorithm
- Combinatorial Optimization
- Exact FHMM
- Discriminative Sparse Coding
- Additive FHMM
- Additive FHMM with SAC (Signal Aggregate Constraints)
- Denoising Auto Encoder
- RNN
- WindowGRU
- Seq2Point
- Seq2Seq

# Notebooks
Algorithms such as AFHMM, AFHMM with SAC and Discriminative Sparse Coding are CPU intensive. All the neural networks are GPU intensive, so the a single experiment had to be run of different types of machines. All the CPU intensive algorithms were run on very powerful CPU system and every other algorithm was run on a system with a GPU. So, for every experiment we have  two different notebooks - one for CPU algorithms and another for everything else. 

