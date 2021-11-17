In adaptive thresholding, every pixel in an image is given a threshold. 
In the so called niblack method, T(i,j)=m(i,j)+k*sigma(i,j), where
k=-0.2 is a constant.
m(i,j) is the mean of the pixels in the neighborhood of the one located at (i,j)
sigma(i,j) is the standard deviation similarly calculated.
T(i,j) is the threshold for pixel at (i,j)
Take 3x3 neighborhood as an example, it contains 9 pixels, 
they are located at (-1,-1), (0, -1), (1, -1)
			        ( -1,0), (0, 0), (1, 0 )
					(-1, 1), (0, 1), (1, 1)
the locations are given relative to the center pixel (here (0,0) )
The aim of this assignment is to implement the above adaptive thresholding method.
The prototype code named AdaptiveThresholding.py is provided, one's implementation should
present in function NiblackThresholding, which receives an numpy array, and a window size as input, and should
return a binarized version of the input image.
For turning in, submit AdaptiveThresholding.py containing implementation code to your repository.
One can test implementation in the block following if __name__=='__main__'
Note: never leave testing or debugging code in the final submission.

    
