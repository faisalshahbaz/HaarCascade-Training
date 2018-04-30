# HaarCascade-Training
Easy way to HaarCascade Training in python.

# Requirment.
Python 2.7, 
Numpy, 
opencv

# Command-run
opencv_traincascade -data ./out/ -vec ./positive/vecfile.vec -bg ./negative/negative.txt -w 120 -h 60 -numPos 99 -numNeg 5  -featureType HAAR -numStages 20
