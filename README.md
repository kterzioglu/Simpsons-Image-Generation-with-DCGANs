# Simpsons-Image-Generation-with-DCGANs
Simpsons Image Generation with DCGANs (Keras Implementation)


Implemented Deep Convolutional GANs (DCGANs) to generate Simpsons character images based on a tutorial dataset (~5k cropped faces). Preprocessed: resized 128x128 to 64x64, normalized. Built generator (upsampling conv layers from noise vector) and discriminator (downsampling conv layers for real/fake classification). Adapted TensorFlow code fully to Keras, adjusted architecture for smaller inputs, defined adversarial loss. Trained for 50+ epochs (Colab/GPU), plotting generated samples per epoch to monitor learning (e.g., improved coherence over time). Interpreted results: Early epochs noisy, later ones captured features like eyes/hair. Submitted notebook with code, comments, visuals, and analysis. AI certificate coursework.


