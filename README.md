# Pokemon_PCA
A demonstration of Principal Component Analysis (PCA) via the MNIST digit dataset and Pokemon images. Professor Peter Sadowski's 
[PCA GitHub repo](https://github.com/peterjsadowski/pokemon_pca/blob/main/PokemonPCA.ipynb) was used as a guideline for understanding PCA. 

This notebook first gets the principal components of 
[images of pokemon](https://raw.githubusercontent.com/peterjsadowski/pokemon_pca/main/data/pokemon_mnist/pokemon_mnist_images.csv) and reconstructs the 
images using their PCA eigenvectors. It then performs this same reconstruction on the [MNIST digits dataset](https://www.tensorflow.org/datasets/catalog/mnist).
Finally, transfer learning is performed. The pokemon images are embedded into the MNIST PCA space and mapped back into image space. This demonstrates the k value 
required to start to successfully reconstruct the pokemon images after the transfer learning.

### Principal Components of Pokemon
<img class="ui image" src="https://robert-lemon-uhm.github.io/images/pokemon_pca.png">

### Principal Components of MNIST
<img class="ui image" src="https://robert-lemon-uhm.github.io/images/mnist_pca.png">

### Transfer Learning
<img class="ui image" src="https://robert-lemon-uhm.github.io/images/transfer_pca.png">
