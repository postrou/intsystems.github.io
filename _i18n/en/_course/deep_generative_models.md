### About
The course is devoted to modern generative models (mostly in the application to computer vision). Special attention is paid to the properties of various classes of generative models, their interrelationships, theoretical prerequisites and methods of quality assessment. The aim of the course is to introduce the student to widely used advanced methods of deep learning.

### Syllabus
1. Generative models overview and motivation. Problem statement. Divergence minimization framework. Autoregressive modelling.
2. Autoregressive models (WaveNet, PixelCNN). Bayesian Framework. Latent Variable Models (LVM). Variational lower bound (ELBO). 
3. EM-algorithm, amortized inference. ELBO gradients, reparametrization trick. Variational Autoencoder (VAE). 
4. VAE limitations. Posterior collapse and decoder weakening. Tighter ELBO (IWAE). Normalizing flows prerequisities.
5. Normalizing Flow (NF) intuition and definition.. Forward and reverse KL divergence for NF. Linear flows. 
6. Autoregressive flows (gausian AR NF/inverse gaussian AR NF). Coupling layer (RealNVP). NF as VAE model.
7. Discrete data vs continuous model. Model discretization (PixelCNN++). Data dequantization: uniform and variational (Flow++). ELBO surgery and optimal VAE prior. Flow-based VAE prior.
8. Flows-based VAE posterior vs flow-based VAE prior. Likelihood-free learning. GAN optimality theorem. 
9. Vanishing gradients and mode collapse, KL vs JS divergences. Adversarial Variational Bayes. Wasserstein distance. Wasserstein GAN  (WGAN). 
10. WGAN with gradient penality (WGAN-GP). Spectral Normalization GAN (SNGAN). f-divergence minimization. Evaluation of implicit models.
11. GAN evaluation (Inception score, FID, Precision-Recall, truncation trick). Discrete VAE latent representations.  
12. Vector quantization, straight-through gradient estimation (VQ-VAE). Gumbel-softmax trick (DALL-E). Neural ODE. Adjoint method. 
13. Continuous-in-time NF (FFJORD, Hutchinson's trace estimator). Kolmogorov-Fokker-Planck equation and Langevin dynamic. SDE basics. Score matching (Sliced score matching, denoising score matching). 
14. Noise conditioned score network (NCSN). Gaussian diffusion process. Denoising diffusion probabilistic model (DDPM).

### Labworks
6 homeworks: theory and practice.

### Grading
Each homework gives 13 points + an exam for 26 points. Final score: (number of points / 8) - 2.

### Prerequisites
Statistics, machine learning, deep learning, intro to bayesian inference.
