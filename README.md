# OpenCV

## I/O and GUI
* Reading images from file
* Simple image transformations—resizing and flipping
* Saving images using lossy and lossless compression
* Showing images in an OpenCV window
* Working with UI elements, such as buttons and
trackbars, in an OpenCV window
* Drawing 2D primitives—markers, lines, ellipses,
rectangles, and text
* Handling user input from a keyboard
* Making your app interactive through handling user
* input from a mouse Capturing and showing frames from a camera
* Playing frame stream from video
* Obtaining a frame stream properties
* Writing a frame stream into video
* Jumping between frames in video files


## Handle "Mouse Events":
## Matrices, Colors, & Filters:
* Manipulating matrices-creating, filling, accessing elements, and ROIs
* Converting between different data types and scaling values
* Non-image data persistence using NumPy
* Manipulating image channels
* Converting images from one color space to another
* Gamma correction and per-element math
* Mean/variance image normalization
* Computing image histograms
* Equalizing image histograms
* Removing noise using Gaussian, median, and bilateral filters
* Computing gradient images using Sobel filters
* Creating and applying your own filter
* Processing images with real-valued Gabor filters
* Going from the spatial to the frequency domain (and back) using discrete Fourier transform
* Manipulating image frequencies for image filtration
* Processing images with different thresholds 
* Morphological operators
* Binary images-image masks and binary operations

## Contours & Segmentation:
* Binarization of grayscale images using the Otsu algorithm
* Finding external and internal contours in a binaryimage
* Extracting connected components from a binary image
* Fitting lines and circles into two-dimensional point sets
* Calculating image moments
* Working with curves - approximation, length, and area
* Checking whether a point is within a contour
* Computing the distance to a two-dimensional point set from every pixel
* Image segmentation using the k-means algorithm
* Image segmentation using segment seeds, the watershed algorithm

## Object Detection and Machine Learning
* Finding edges using the Canny algorithm
* Detecting lines and circles using the Hough transform
* Finding objects via template matching
* The real-time median-flow object tracker
vTracking objects using different algorithms via the
tracking API
* Computing the dense optical flow between two frames
* Detecting chessboard and circle grid patterns
A simple pedestrian detector using the SVM model
Optical character recognition using different machine
learning models
* Detecting faces using Haar/LBP cascades
* Detecting AruCo patterns for AR applications
* Detecting text in natural scenes
* The QR code detector and recognizer

## Image and Video
* Processing
* This chapter contains recipes for:
* Warping an image using affine and perspective transformations
* Remapping an image using arbitrary transformation
* Tracking keypoints between frames using the Lucas-Kanade algorithm
* Background subtraction
* Stitching many images into panorama
* Denoising a photo using non-local means algorithms
* Constructing an HDR image
* Removing defects from a photo with image inpainting

## Detectors and Descriptors
* This chapter contains recipes for:
* Finding corners in an image - Harris and FAST
* Selecting good corners in an image for tracking
* Drawing keypoints, descriptors, and matches
* Detecting scale invariant keypoints
* Computing descriptors for image keypoints - SURF, BRIEF, and ORB
* Matching techniques for finding correspondencesbetween descriptors
* Finding reliable matches - cross-check and ratio test
* Model-based filtering of matches - RANSAC
* BoW model for constructing global image descriptors



## Multiple View Geometry:
* Pinhole camera model calibration
* Fisheye camera model calibration
* Stereo rig calibration - estimation of extrinsics
* Distorting and undistorting points
* Removing lens distortion effects from an image
* Restoring a 3D point from two observations through triangulation
* Finding a relative camera-object pose through the PnP algorithm
* Aligning two views through stereo rectification
* Epipolar geometry - computing fundamental and essential matrices
* Essential matrix decomposition into rotation and translation
* Estimating disparity maps for stereo images
* Special case 2-view geometry - estimating homography transformation
* Planar scene - decomposing homography into rotation and translation
* Rotational camera cas - estimating camera rotation from homography
