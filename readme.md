# Image Forgery Detection

With over 4.5 billion active internet users, the amount of multimedia content being shared every day has surpassed everyone’s imagination. Large-scale and pervading social media platforms, along with easily accessible smartphones, have given rise to huge visual data such as images, videos, etc. One of the perils accompanying this huge amount of data is manipulation and malicious intent to remove the authenticity
of these media. The availability of various image-editing software and tools such as Photoshop, GIMP, etc., has made it possible to create forgeries with minimal effort. Today, it is quite easy to produce a manipulated media that looks indifferent to the human eyes. 

Various types of digital image forgeries have evolved, the major ones include **copy-move, splicing, morphing, watermarking**, etc. Copy-move manipulation means cutting and pasting a portion of the same image onto itself. Splicing involves cutting and pasting from different sources.

Techniques designed to detect these forgeries can be divided into two classes based on how they use an image to extract its feature, one that uses handcrafted features and the other deep-learning-based extracted features. These techniques either solve for detection of forged images or detection as well as localisation of the tampered region.

### Reproduced Code
In this repository, I have tried to implement 5 papers of which are solving for image forgery detection using handcrafted features from images.
There are 5 folders named after the authors containing the code for each paper. The datasets used are [CASIA 1.0](https://github.com/namtpham/casia1groundtruth), [CASIA 2.0](https://github.com/namtpham/casia2groundtruth), [Columbia Colored](https://www.ee.columbia.edu/ln/dvmm/downloads/AuthSplicedDataSet/AuthSplicedDataSet.htm), and [Columbia Uncompressed](https://www.ee.columbia.edu/ln/dvmm/downloads/authsplcuncmp/)

#### Papers
1. [Passive detection of image forgery using dct and local binary pattern by Alahmadi et al.](https://doi.org/10.1007/s11760-016-0899-0)
2. [Image forgery detection based on statistical features of block dct coefficients by Shilpa et al.](https://www.sciencedirect.com/science/article/pii/S1877050920310048)
3. [A novel forgery detection algorithm based on mantissa distribution in digital images by Arman et al.](https://ieeexplore.ieee.org/document/9349611)
4. [A passive blind approach for image splicing detection based on dwt and lbp histograms by Mandeep et al.](https://link.springer.com/chapter/10.1007/978-981-10-2738-3_27)
5. [A robust forgery detection method for copy–move and splicing attacks in images by Mohammad et al.](https://www.mdpi.com/2079-9292/9/9/1500)

#### Results
The reproduced results in terms of **accuracy** are shown below. The numbers in bracket represent the original results given in the papers.

![Reproduced Result](./results.png)


To get these codes, just **fork** the repository into your local system. Then create a virtual environment and run the `requirements.txt` to download the necessary packages. You can also use the extracted features given in CSVs. Please cite the papers and give due credits to this repository if you use it anywhere. ***CHEERS!***

