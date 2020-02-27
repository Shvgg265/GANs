# GANs

Generative adversarial networks (GANs) are algorithmic architectures that use two neural networks, 
pitting one against the other (thus the “adversarial”) in order to generate new, 
synthetic instances of data that can pass for real data. 
They are used widely in image generation, video generation and voice generation.

The generative network generates candidates while the discriminative network evaluates them. The contest operates in terms of data distributions. Typically, the generative network learns to map from a latent space to a data distribution of interest, while the discriminative network distinguishes candidates produced by the generator from the true data distribution. The generative network's training objective is to increase the error rate of the discriminative network (i.e., "fool" the discriminator network by producing novel candidates that the discriminator thinks are not synthesized (are part of the true data distribution)).
