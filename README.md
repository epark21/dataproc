# Individual Project 3
# Distributed Image Processing in Cloud Dataproc

Goals
- Learn to use Apache Spark on Cloud Dataproc to distribute an image processing task onto a cluster of machines.
- Create a managed Cloud Dataproc cluster with Apache Spark pre-installed.
- Build and run jobs that use external packages that aren't already installed on your cluster.

# 1. Create a development machine in Compute Engine > VM Instances
![Image](../master/images/1.png?raw=true)

# 2. SSH into the instance and create SSH keys
![Image](../master/images/2.png?raw=true)
![Image](../master/images/4.png?raw=true)

# 3. Add SSH keys to Github
![Image](../master/images/3.png?raw=true)

# 4. Git Clone
![Image](../master/images/5.png?raw=true)

# 5. Set up Scala and sbt
![Image](../master/images/6.png?raw=true)

# 6. Set up the Feature Detector Files
```
sudo apt-get update
git clone https://github.com/GoogleCloudPlatform/cloud-dataproc
cd cloud-dataproc/codelabs/opencv-haarcascade
```

# 7. Launch Build
```
sbt assembly
```

# 8. Create a GCS bucket and collect images
![Image](../master/images/7.png?raw=true)
![Image](../master/images/8.png?raw=true)

# 9. Take a look at your bucket and images on GCP
![Image](../master/images/9.png?raw=true)
![Image](../master/images/10.png?raw=true)
 
# 10.	Create a Cloud Dataproc Cluster
![Image](../master/images/11.png?raw=true)

# 11.	Submit job to Dataproc
![Image](../master/images/12.png?raw=true)
![Image](../master/images/13.png?raw=true)

# 12.	Check our bucket in Storage – Out Directory
![Image](../master/images/14.png?raw=true)
![Image](../master/images/15.png?raw=true)
