#What are Autoencoders?
*Neural Networks with encoder function that reduces the dimensionality of the image and a decoder that reconstructs the original image from the encoded output
*autoencoders should not copy the image pperfectly. Instead, by reducing dimensionality, it is forced to pick up the key characteistics

#Regularized Autoencoders
*use a different loss function to prevent copying of input to output
*loss funcions are: sparsity of representation, robustness to noise or missing inputs,etc
* sparse autoencoders: L(x, g(f(x))) + Ω(h), where g(h) is the decoder output, and typically we have h=f(x), the encoder output
* key idea: use maximum log liklihood

#Denoising Autoencoders
*minimise L(x, g(f(˜x))) where˜xis a copy of x that has been corrupted by some form of noise
*receives corrupted data point and trained to output uncorrupted data point

#Applications
*dimensionality reduction to improve performance
# make search faster
