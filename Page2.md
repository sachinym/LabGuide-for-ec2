<h1 align="middle"> Getting Started with EC2 </h1>

---

### Launching your first EC2 instance

1. Click on **Launch instance** or you can go the the **instances** in the left panel and then click on **Launch instance**.

![](./Screenshot/launch_instance.png)

2. Provide a name for your EC2 instance. 

![](./Screenshot/name_instance.png)

3. Select an Amazon Machine Image (ami) of your choice and preference.
  
![](./Screenshot/select_ami.png){#section-1} 

4. Select an instance type that meets your computing, memory, networking, or storage needs.

![](./Screenshot/instance_type.png)

5. In the Key pair login section, you need to create new key pair. Select **Create new key pair** option. 

![](./Screenshot/select_keypair.png)

6. Provide a name for key pair which should be unique everytime. Then, click on **Create key pair** which will create a new key pair.

> When the key pair is created, a file with private key file format (.pem or .ppk) is downloaded to your system. Use that key to access your instance when logging in through ssh client.

![](./Screenshot/create_keypair.png)

7. Keep the Network Settings as it is.

> **NOTE:** Default network which is present in every region, will be selected if no settings is done.

![](./Screenshot/select_network.png)

8. Specify the storage type to use in the instance based on your preference.

![](./Screenshot/select_storage.png)

9. After selecting your preferences, click on Launch instance which will create your instance.

![](./Screenshot/create_instance.png)
