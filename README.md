# Transformation parameters

a_r = 3.0  
b_r = 1.2

# GAN architecture description

GAN used has 2 small neural networks, one for generator and one for discriminator. They compete with each other while learning the data distribution.  
generator takes random noise as input and learns to produce fake samples of transformed variable z.  
discriminator receives either real or generated z and predicts whether they are real or fake.  
Both networks use ReLU activation. The discriminator uses sigmoid output to produce probability score.  
Through this competition, generator learns the probability distribution of z using data only.  

# PDF plot obtained from GAN samples
