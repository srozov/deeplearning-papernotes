A somewhat complicated paper. The idea is twofold: background attenuation and using multiple frames in a video for segmentation. Second is pretty simple. A couple of frames are fed into the network to segment. The first is a bit more complicated. Some background patches are fed into a CNN, globally pooled and then fed into another network that works on top of the feature maps from the original image and the background patches. It’s pretty fast and kind of accurate, but it is highly optimized.