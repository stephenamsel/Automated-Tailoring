This code is useful for detecting objects in high-interference images.

It applies the Canny algorithm to identify pixels that may be on edges of objects. Then it "follows" edges, starting from ends, the same way that the human eye does to connect the edge-pixels and outline the object. It will produce many false positives, but if you can model the interference, a chi-squared fit comparing the numbers of edges in bins of different lengths should tell you whether or not there are objects in the image. A general solution to object-recognition is beyond the scope of this program.
