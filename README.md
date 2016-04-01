# The objective of this project is to automate manufacturing of parts from omages.

#The stack is to run as follows:
#Image analysis software reads images as numerical arrays - (find a library)
#Noise, lighting, etc. is filtered out and objects are found - Canny Algorithm
#A 3D model is built from the images if necessary - (find / produce an algorithm)
#Manufacturing machinery is sent signals to produce the objects in the image - based on robotic arm-control
