# K-Means Clustering Using Spark on AWS

In this repo, I demo the use of Amazon Web Services (AWS) SageMaker to do clustering on MNIST images using Apach Spark. MNIST is a dataset of 70,000 grayscale images of handwritten digits of size 28x28. The size of the MNIST dataset motivates the use of distributed computing via Spark for fast and efficient modeling. Please check **pyspark_mnist_kmeans.ipynb** for the code used in this demo.

Demo Video: https://www.youtube.com/watch?v=v_bCTgwSHPI

### Setup

When replicating this demo via AWS SageMaker, please ensure that you IAM roles have been properly configured. Using the following IAM roles should allow for a full replication of the demo:

```bash
AmazonS3FullAccess
AmazonSageMakerFullAccess
```

### Results

Examples of cluster predictions:

<img src="https://github.com/AltamashRafiq/sparkkmeans/blob/main/img1.png" width="300" height="300">

<img src="https://github.com/AltamashRafiq/sparkkmeans/blob/main/img2.png" width="300" height="300">
