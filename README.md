# Image Translation Projects

## CycleGAN

CycleGAN is an unpaired image-to-image translation model that learns to convert images from one domain to another without needing matched training pairs. It uses two generators and two discriminators along with a cycle-consistency loss to ensure that translating an image from domain A to B and back again returns the original image. Common use cases include horse-to-zebra, summer-to-winter, and photo-to-painting style transfers.

## Image-to-Image Translation (Pix2Pix)

Pix2Pix is a paired image-to-image translation model that uses a conditional GAN to learn a mapping from an input image to a corresponding output image. Unlike CycleGAN, it requires matched image pairs during training, making it better suited for tasks where precise pixel-level correspondence matters, such as converting sketch to photo, label map to scene, or aerial photo to map.