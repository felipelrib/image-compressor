# Image Compressor

This is a very simple grayscale image compressor, created as an assignment for the Introduction to Visual Computing college course. 

## How it works

It takes a .pgm file (raw grayscale image with one byte per pixel) and applies both the predictive code compressing and Huffman coding compression and generating a .mycompress file, which can be uncompressed and seen directly in the notebook. Both methods can be parameterized to be or not to be used, but, due to the need to generate a binary file after the compression, Huffman coding will be replaced with a generic binary coding algorithm. This compression is lossless and this property can be verified at the end. The compression rate can also be shown, to compare both algorithms and the efficiency of its possible combinations.
