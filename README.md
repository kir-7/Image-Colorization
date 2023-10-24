# Image-Colorization
This my attempt at implementing image colorization using the Pix2Pix GAN Model 

Original attempt: https://phillipi.github.io/pix2pix/

Due to lack of training infrastructure trained for only 3k steps but recommended for around 40k steps

results after 3k steps of training:
  ![trial](https://github.com/kir-7/Image-Colorization/assets/114975306/6065e71b-53ab-4c8b-989e-468d340928fc)
![Screenshot (182)](https://github.com/kir-7/Image-Colorization/assets/114975306/2bc0c91a-6fe6-4a20-8844-7e491077b772)


Even though trained only for 3k steps still generated decent images
# Model Architechture
    Generator Model:

![base_generator_mmodel (1)](https://github.com/kir-7/Image-Colorization/assets/114975306/811c4f38-a5d3-4304-be32-6c2b96f3d809)
  
    Discriminator Model

![base_discriminator_mmodel](https://github.com/kir-7/Image-Colorization/assets/114975306/ceac8f66-0b5f-41a3-8c66-bbbf617d2cf1)
