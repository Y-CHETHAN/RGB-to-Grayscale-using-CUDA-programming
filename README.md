# CUDA Grayscale Conversion

## Aim:
The aim of this project is to demonstrate how to convert an image to grayscale using CUDA programming without relying on the OpenCV library. It serves as an example of GPU-accelerated image processing using CUDA.

## Procedure:
1. Load the input image using the `stb_image` library.
2. Allocate memory on the GPU for the input and output image buffers.
3. Copy the input image data from the CPU to the GPU.
4. Define a CUDA kernel function that performs the grayscale conversion on each pixel of the image.
5. Launch the CUDA kernel with appropriate grid and block dimensions.
6. Copy the resulting grayscale image data from the GPU back to the CPU.
7. Save the grayscale image using the `stb_image_write` library.
8. Clean up allocated memory.

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
## Output:

### Input file:

![RGB](https://github.com/Marinto-Richee/RGB-to-Grayscale-using-CUDA-programming/assets/65499285/4dae3099-3090-4ff8-8a22-41f0603a38b3)

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

### Output file:

![output_image](https://github.com/Marinto-Richee/RGB-to-Grayscale-using-CUDA-programming/assets/65499285/94868e77-8530-4915-a5ea-fab0c24aec1e)


## Result:
The CUDA program successfully converts the input image to grayscale using the GPU. The resulting grayscale image is saved as an output file. This example demonstrates the power of GPU parallelism in accelerating image processing tasks.
