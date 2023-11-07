# Image-Colorization-using-GANs

Image colorization is of great use for several appli- cations, such as the restoration of
old images, as well as enabling the storage of grayscale images, which take up less
space, which can later be colorized. But this problem is hard since there exist many
possible color combinations for a particular grayscale image. Recent developments
have aimed to solve this problem using deep learning. But, for achieving good
performance, they require highly processed inputs, along with additional elements,
such as semantic maps. To overcome abnormal colors and to improve image quality
with good colorization we are using Generative Adversarial Network (GAN).

The process of colorization using GANs involves two neural networks: a gen-
erator network and a discriminator network. The generator network is trained to
generate synthetic images that are similar to the input images, while the discrimi-
nator network is trained to distinguish between synthetic and real images.
During training, the generator network generates a synthetic image and the
discriminator network determines whether the image is real or synthetic. If the
discriminator network determines that the image is real, the generator network is
rewarded and its performance is improved. If the discriminator network determines
that the image is synthetic, the generator network is penalized and its performance
is degraded. This process is repeated until the generator network is able to generate
synthetic images that are indistinguishable from real images.Once trained, the
generator network can be used to colorize grayscale images by inputting a grayscale
image and generating a colorized version of the image. This can be useful for a
variety of applications, including restoring old photographs and adding color to
black and white movies.
