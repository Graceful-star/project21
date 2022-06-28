# DOCUMENTATION OF PROJECT 21

1. I created the necessary AWS cloud resources for kubernetes cluster

   
    ![Projec21](images/image1.PNG)
     ![Projec21](images/image2.PNG)
     ![Projec21](images/image3.PNG)
     ![Projec21](images/image4.PNG)
     ![Projec21](images/image9.PNG)
     ![Projec21](images/image10.PNG)
     


2. I checked what was created on aws console

    ![Projec21](images/image5.PNG)
     ![Projec21](images/image6.PNG)
     ![Projec21](images/image7.PNG)
     ![Projec21](images/image8.PNG)

3. I created Compute reourses;

a. Image ID
b. keypair
c. Instances for control planes
d. Instances for worker nodes

![Projec21](images/image11.PNG)
     ![Projec21](images/image12.PNG)
     ![Projec21](images/image13.PNG)
     ![Projec21](images/image14.PNG)
     ![Projec21](images/image15.PNG)
     ![Projec21](images/image16.PNG)
     ![Projec21](images/image17.PNG)
     ![Projec21](images/image18.PNG)

4. I prepared the certificate authority and generated TLS certificates

     ![Projec21](images/image19.PNG)
     ![Projec21](images/image20.PNG)
     ![Projec21](images/image21.PNG)
     ![Projec21](images/image22.PNG)
     ![Projec21](images/image23.PNG)
     ![Projec21](images/image24.PNG)
     ![Projec21](images/image25.PNG)
     ![Projec21](images/image26.PNG)
     ![Projec21](images/image27.PNG)
     ![Projec21](images/image28.PNG)
     ![Projec21](images/image29.PNG)
     ![Projec21](images/image30.PNG)
     ![Projec21](images/image31.PNG)
     ![Projec21](images/image32.PNG)
     ![Projec21](images/image33.PNG)
     ![Projec21](images/image34.PNG)
     ![Projec21](images/image35.PNG)
     ![Projec21](images/image36.PNG)
     ![Projec21](images/image37.PNG)
     ![Projec21](images/image38.PNG)
     ![Projec21](images/image39.PNG)
     ![Projec21](images/image40.PNG)
     ![Projec21](images/image41.PNG)


5. I prepared the etcd database for encryption at rest

    ![Projec21](images/image42.PNG)

6. I created an encryption-config.yaml file according to kubernetes

   ![Projec21](images/image43.PNG)
  
7. Then I ssh into the master nodes one after the other and ran the necessary commands

   
   ![Projec21](images/image44.PNG)
   ![Projec21](images/image45.PNG)
   ![Projec21](images/image46.PNG)
   ![Projec21](images/image47.PNG)
   ![Projec21](images/image48.PNG)
   ![Projec21](images/image49.PNG)
   ![Projec21](images/image50.PNG)
   ![Projec21](images/image51.PNG)

8. I verified if the ETCD server is running
    ![Projec21](images/image52.PNG)

9. I configured the components for the control plane on the master nodes

   ![Projec21](images/image53.PNG)
   ![Projec21](images/image54.PNG)
   ![Projec21](images/image55.PNG)
   ![Projec21](images/image56.PNG)

10. Then I tested evrything to see if it's working fine

   ![Projec21](images/image57.PNG)
   ![Projec21](images/image58.PNG)
   ![Projec21](images/image59.PNG)
   ![Projec21](images/image60.PNG)


11. I configured the worker nodes, installed containerd and verified if everything is working

   ![Projec21](images/image61.PNG)
   ![Projec21](images/image62.PNG)
   ![Projec21](images/image63.PNG)
   ![Projec21](images/image64.PNG)
   ![Projec21](images/image65.PNG)
   ![Projec21](images/image66.PNG)
   ![Projec21](images/image67.PNG)