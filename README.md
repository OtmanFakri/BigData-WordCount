# Hadoop Master - TP1-TP3

This README provides instructions on running the `hadoop-master-tp1-tp3.tar` Docker image, which contains Hadoop Master with TP1 and TP3  installed.

## Prerequisites

- Docker should be installed and running on your machine.

## Getting Started

1. Download the `hadoop-master-tp1-tp3.tar` image file.

2. Load the image into Docker using the following command:

   ```bash
   docker load -i hadoop-master-tp1-tp3.tar
3. Once the image is loaded, you can run a container based on it using the following command:
   ```bash
   docker run --name hadoop-master -p 8088:8088 -p 9870:9870 hadoop-master-tp1-tp3
 This command starts a container named hadoop-master based on the hadoop-master-tp1-tp3 image. It maps container ports 8088 and 9870 to the corresponding ports on your local machine, allowing access to the Hadoop Web UI.
4. After running the container, you can access the Hadoop Web UI in your browser at the following URLs:

    Resource Manager: http://localhost:8088
    NameNode: http://localhost:9870

