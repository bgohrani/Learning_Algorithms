# Optimization and Learning Algorithms

## Hey There!

This notebook covers concepts related to different learning algorithms that could be used to train models in FeedForward Neural Networks. The intuition behind having different training methods is to cover diverse forms of data that might have to be used. A typical example is that sometimes the loss function value generated may be very high indicating a need for training but may change very little in a local region for any given weight. Since the magnitude is small, the update made to the weights would also be small leading to very long times for convergence as the model could be stuck in small region without updates. In such cases, it is necessary to look at newer algorithms which could tackle such problems and lead to faster convergence. This is what will be explored in the notebook. The networks built in this notebook have been thoroughly explained in my [FeedForward Neural Networks Repository](https://github.com/bgohrani/FeedForward_Networks)

Notebook Outline:
- Generating blob data for training.
- Writing down classes for specific and general FeedForward Networks, implementing many different learning algorithms.
- Writing down classes for implmenting newer activation functions and weight initializations and observing how training improves.
- Running a loop for training with different initialisations and activations and visualizing how weights change to train the model.
