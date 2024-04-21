# TiltRec
This is the support data for TiltRec

The BBb dataset is a tilt-series dataset consisting of cellular slices focused on the centrosome region. It includes 64 projections, each with an image size of 1024×1024 pixels. The angular ranges span from –61.0◦ to +65.0◦, spaced at 2◦ intervals. The data were downloaded from the IMOD tutorial and were acquired using an FEI TF39 microscope operating at 300kV and a Gatan camera. Each tilt image has dimensions of 1024×1024 pixels with a pixel size of 1.01 nanometers. The size of the reconstructed 3D volume is 1024×1024×300, approximately 1.2 GB.

The V4B dataset is a tilt-series dataset containing 21 projections. Each tilt image has dimensions of 1536×2048 pixels with a pixel size of 0.2 nanometers per pixel. The angular ranges span from –50.0◦ to +50.0◦, spaced at 5◦ intervals. The size of the reconstructed 3D volume is 3072 × 4096 × 300, approximately 15 GB.

The EMPIAR-10045 dataset includes raw data of purified brewing yeast 80S ribosomes. including 31 projection sequences. Each projection sequence measures 3838 × 3710. The angular range spans from –57.9◦ to 29.4.0◦, with an interval of 3.0◦. The size of the reconstructed 3D volume for this dataset reaches up to 60 GB, exceeding the memory capacity of most GPU. This serves as an effective test for the performance of CUDA-accelerated reconstruction software under such conditions.
