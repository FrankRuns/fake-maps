# fake-maps
Tools for creating fake maps with GANs

1. Use create-tiles.ipynb to generate map image training data. The notebook has a few cells for testing (different image sizes, zoom level) as well as a function to create hundreds (1000s?) of images to be saved to your /images directory. I included 20 sample images to start.

2. In the run_gans/DCGAN256-keras directory, use the build-fake-maps.ipynb file to build your model and generate new 256x256 images. Note that there's 20 images in the images directory... but you'll need many more images than that to get actual results.

3. In the run_gans/udacity-DCGAN32 directory, use the udacity-DCGAN.ipynb file to build your model and generate new 32x32 images. Note that there's 20 images in the images directory... but you'll need many more images than that to get actual results. ALSO, this is one of the template notebooks used in the course for face generation - it's not as clean as it should be. Plus the directories are not seamless, they refer to my laptop. 

## Sample output from the DCGAN256 model

![](results/dcgan256_99.png)