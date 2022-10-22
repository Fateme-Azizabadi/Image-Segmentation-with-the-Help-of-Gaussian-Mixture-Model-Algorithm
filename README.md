# Image Segmentation with the Help of Gaussian Mixture Model Algorithm

**Image Segmentation with the Help of Gaussian Mixture Model Algorithm**

**In this project, we used the Gaussian Mixture Model to solve the image segmentation problem. In this problem, the goal is to separate the features of the image. We deal with a particular type of this problem: separation by image colors.**


## **Implementation**
Gaussian Mixture Model has been implemented in Python as a class with the help of the EM algorithm, and each of the functions is given in the notebook of this question with the explanation of how they work.
At first, the GMM class is implemented from scratch, and at the end, the Gaussian Mixture of the sklearn.mixture library is brought only for comparison.

## **Result**

We have implemented the GMM class to have six color categories and draw their contours.
As you can see, the colors are divided into 6 clusters. (The number of clusters is considered 6.)

 ![](https://github.com/Fateme-Azizabadi/Image-Segmentation-with-the-Help-of-Gaussian-Mixture-Model-Algorithm/blob/main/Images/k.png)


We divided the colors of the image into six categories with the help of GMM class, then placed the mean of the corresponding Gaussian distribution in its place and drew the image.

 ![](https://github.com/Fateme-Azizabadi/Image-Segmentation-with-the-Help-of-Gaussian-Mixture-Model-Algorithm/blob/main/Images/ponyo.png)

 ![](https://github.com/Fateme-Azizabadi/Image-Segmentation-with-the-Help-of-Gaussian-Mixture-Model-Algorithm/blob/main/Images/Result.png)


