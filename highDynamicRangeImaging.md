#High Dynamic Range(HDR) Imaging

## Table of Contents
- [Books](#books)
- [Courses](#courses)
- [Papers](#papers)
- [Software](#software)
- [Datasets](#datasets)
- [Tutorials and Talks](#tutorials-and-talks)
- [Resources for students](#resources-for-students)
- [Links](#links)
- [Licenses](#licenses)

## Books
### General Introdution
 - [High dynamic range imaging: acquisition, display, and image-based lighting](https://books.google.com.tw/books?hl=zh-TW&lr=&id=w1i_1kejoYcC&oi=fnd&pg=PP2&dq=High+dynamic+range+imaging:+acquisition,+display,+and+image-based+lighting.&ots=4i-28zQHpB&sig=7ImiQtgMxdPvwtMPQQIYMyiBfn8&redir_esc=y#v=onepage&q=High%20dynamic%20range%20imaging%3A%20acquisition%2C%20display%2C%20and%20image-based%20lighting.&f=false)
	+ Reinhard, Erik, et al. ,2010
	+ The bible of the HDR imaging

## Courses

## Papers
### HDR image reconstruction
- Debevec, Paul E., and Jitendra Malik. "Recovering high dynamic range radiance maps from photographs." Proceedings of the 24th annual conference on Computer graphics and interactive techniques. ACM Press/Addison-Wesley Publishing Co., 1997.
	+ The basic but effective method for HDR image reconstruction, this paper motivates many works about HDR imaging
	+ Matrix form solution(including least square term and smoothness term)
- Robertson, Mark, Sean Borman, and Robert L. Stevenson. "Dynamic range improvement through multiple exposures." Image Processing, 1999. ICIP 99. Proceedings. 1999 International Conference on. Vol. 3. IEEE, 1999.
	+ Maximum likelihood solution, consider the additive noise and dequantization error as independent Gaussian random variable
	+ Iterative method
- Mitsunaga, Tomoo, and Shree K. Nayar. "Radiometric self calibration." Computer Vision and Pattern Recognition, 1999. IEEE Computer Society Conference on.. Vol. 1. IEEE, 1999.
	+ Use polynomials to model the CRF
	+ Iterative method with rough estimation of exposure time ratio

### Tone mapping

### Alternative to HDR imaging
- Exposure Fusion
	+ Two series of paper
		+ Mertens, Tom, Jan Kautz, and Frank Van Reeth. "Exposure fusion." Computer Graphics and Applications, 2007. PG'07. 15th Pacific Conference on. IEEE, 2007.
		+ Mertens, Tom, Jan Kautz, and Frank Van Reeth. "Exposure fusion: A simple and practical alternative to high dynamic range photography." Computer Graphics Forum. Vol. 28. No. 1. Blackwell Publishing Ltd, 2009.
			+ Scalar-weighted map is first generated based on the quality measurement (contrast, saturation, well-exposedness) of the exposure bracketed image, then the fusion is performed in the multiresolution manner (Gaussian pyramids of the weighted map and Laplacian pyramids of the original image)

## Software
- [HDR_Toolbox](https://github.com/banterle/HDR_Toolbox)
	+ HDR Toolbox for processing High Dynamic Range (HDR) images into MATLAB and Octave
	+ The most complete HDR imaging related tool for research

## Datasets
- [Empa HDR Image Database](http://www.empamedia.ethz.ch/hdrdatabase/index.php)
- [HDR_Dataset](https://github.com/hsiaoyi0504/HDR_Dataset)
	+ My collection of some HDR dataset (under construction)

## Tutorials and Talks

## Resources for students

## Links

## Licenses
License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [hsiaoyi0504](https://github.com/hsiaoyi0504) has waived all copyright and related or neighboring rights to this work.
