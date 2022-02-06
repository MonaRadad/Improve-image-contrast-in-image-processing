# Improve-image-contrast-in-image-processing
In this project, we increase the image contrast with the help of histogram equalization.
He3, He2, He1, and He4 images are images that we want to improve by contrast
If the input image is called f and the HE-enhanced image is called fhe. For different values, α from 0.1 to 0.5 with a step of 0.1 image
We obtain g = α.f + (1-α) fhe and display the result.
We performed localized histogram (LHE) on these images using 151 * 151, 101 * 101, 51 * 51, and 201 * 201 windows and increased the LHE speed by moving the blocks by half a block and interpolation we used.
