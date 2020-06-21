# EE763-Assignment
Partial submission to using Turing for Variational inference

The attempt is to use Automatic differential vairational inference available in Julia (Turing) to solve an Image denoising problem.

The algorithm attempted is:
1. Load an image to program.
2. Create a binary version of it.
3. Define a model incorporating Ising asumptions and liklihood.
4. Perform Variational Inference using ADVI.
5. Find the posterior which should be denoised Image.

I could not completely impliment the denoing part using Ising model. 
I could run the variational inference defining a basic likelihood function and reconstruct the noisy input image reasonably well as a multivariate posterior distribution.
This reconstruction required variational inference as we assumed the noisy image is a pixel wise obervation to a hidden image (posterior attempting to recreate).
The posterior multivariate distribution mentioned can be used to sample many variations of the input noisy image. 
Please look at the input and and output screenshots to see the results.
