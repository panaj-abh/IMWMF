# IMWMF: A class project of 2102676 (Digital Image Processing - 2021/2)
at Department of Electrical Engineering Chulalongkorn University Bangkok, Thailand

Abstract
This project is mainly studied the Iterative Mean Filter (IMF) algorithm in [1] and proposed an improved version
by adopting the weighted mean idea that exploits the Minkowski distance from the center pixel (p=0.125) as
the weighted window with a size of 3 × 3. The proposed filter still uses the constrained mean of the intensity
of noise-free pixels in a fixed-size window to suppress the salt-and-pepper noise in grayscale images.
The experiment was conducted with the same settings as in [1] except that the experiment used only the IMF method
to compare with the proposed one and used the different random seed to generate the noisy images
(the results can’t be the same because we didn’t know the initial random seed they used in [1]).
In conclusion, the experimental results show that the proposed filter outperforms the IMF in almost all cases.

[1] U. Erkan, D. N. H. Thanh, L. M. Hieu, and S. Engínoğlu, “An Iterative Mean Filter for Image Denoising,”
in IEEE Access, vol. 7, pp. 167847–167859, 2019
