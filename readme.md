#Image Forgery Detection

With over 4.5 billion active internet users, the amount of multimedia content being shared every day has surpassed everyone’s imagination. Large-scale and pervading social media platforms, along with easily accessible smartphones, have given rise to huge visual data such as images, videos, etc. One of the perils accompanying this huge amount of data is manipulation and malicious intent to remove the authenticity
of these media. The availability of various image-editing software and tools such as Photoshop, GIMP, etc., has made it possible to create forgeries with minimal effort. Today, it is quite easy to produce a manipulated media that looks indifferent to the human eyes. 

Various types of digital image forgeries have evolved, the major ones include **copy-move, splicing, morphing, watermarking**, etc. Copy-move manipulation means cutting and pasting a portion of the same image onto itself. Splicing involves cutting and pasting from different sources.

Techniques designed to detect these forgeries can be divided into two classes based on how they use an image to extract its feature, one that uses handcrafted features and the other deep-learning-based extracted features. These techniques either solve for detection of forged images or detection as well as localisation of the tampered region.

### Reproduced Code
In this repository, I have tried to implement 5 papers of which are solving for image forgery detection using handcrafted features from images.
There are 5 folders named after the authors containing the code for each paper. The datasets used are [CASIA 1.0](https://github.com/namtpham/casia1groundtruth), [CASIA 2.0](https://github.com/namtpham/casia2groundtruth), [Columbia Colored](https://www.ee.columbia.edu/ln/dvmm/downloads/AuthSplicedDataSet/AuthSplicedDataSet.htm), and [Columbia Uncompressed](https://www.ee.columbia.edu/ln/dvmm/downloads/authsplcuncmp/)

The reproduced results in terms of **accuracy** are shown below. The numbers in bracket represent the original results given in the papers.

![Reproduced Result](./results.png)


To get these codes, just **fork** the repository into your local system. Then create a virtual environment and run the `requirements.txt` to download the necessary packages. You can also use the extracted features given in CSVs. Please cite the papers and give due credits to this repository if you use it anywhere. ***CHEERS!***

