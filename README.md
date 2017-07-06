TMED -- Threshold Modulated Error Diffusion. 

This is the implementation of SIGGRAPH 2003 Technical Paper:
"Improving Mid-tone Quality of Variable-Coefficient Error Diffusion" , by Zhou,BingFeng and Fang,XiFeng

Usage: TMED <input\> <width\> <height\>\
<input\>: 8-bit gray scale image to be halftoned, in RAW format (can be created and opend in PhotoShop) \
<width\>: width of the input image\
<height\>: height of the image

e.g. :

tmed 16steps1020x280.raw 1020 280

This will create a file named Result.raw, which is the error diffusion result of the file 16steps1020x280.raw .



