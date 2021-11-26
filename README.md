# **Neural Architecture Search Using Genetic Algorithm**
## About
_This repository is about searching a suitable Convolutional
Neural Network using Genetic Algorithm on Fashion
MNIST Data-set._ 
- We are denoting each of the neural network using a genome sequence.
- We are trying to find out neural network with minimum paramater and maximum test accuracy.

>This project was actually a part of CSL 7540 - Artificial Intelligence at Indian Institute of Technology Jodhpur as a course project.


## Genetic Algorithm

- Comeup with a fitness function
- Apply this fitness function to select the top 5 best genome sequence as per our fitness score.
- Applying Random Crossover on the best select genome sequence.
- Apply Mutation to these crossed genome sequences.
- Then analyse the efficacy of the mutated genome sequence and add these genomes to your initial population to increase the diversity anomg them.
- If the mutated genome is better than the best genome we are having already then, it our final result.
- Else we would again repeat the entire process.

## Results
- Results for the best genome sequence found
![Results](https://drive.google.com/uc?export=view&id=1HpGl_otxfgd0dSQI1eR-5t657pnItYsj)



- Training Accuracy Vs. Validation Accuracy  and  Training Loss Vs. Validation Loss for the best genome sequence.

![Results](https://drive.google.com/uc?export=view&id=1h2whAqhhL2FnXn3BVT4wNJ9fLDO6RVcK)