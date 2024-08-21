# Docker-Private-Registry

![image](https://github.com/user-attachments/assets/20144850-9e8c-475d-86dc-859ec6a94ee9)



### Step1: Installing docker registry
  ```
  sudo apt update
  ```
  ```
  apt install docker-registry
  ```
  <img width="730" alt="image" src="https://github.com/user-attachments/assets/c4def68e-bd2a-4d6b-9744-c1bd88758730">

### Step 2: Configuring the Docker Registry
* To configure the Docker Registry, we need to modify the registry's configuration file located at '/etc/docker/registry/config.yml'
  ```
  vim /etc/docker/registry/config.yml
  ```
  <img width="436" alt="image" src="https://github.com/user-attachments/assets/c1d3d42d-0297-4d7d-8868-5a30cdde47cb">

### Step 3: Running the Docker Registry
* With the configuration in place, you can start the Docker Registry service using the following command:

* Check the status of running container
  ```
  docker ps | grep cfe037d903f8
  ```
  <img width="777" alt="image" src="https://github.com/user-attachments/assets/f7e48863-bb41-4e0f-b722-b7f70269ba1f">



### Check the url
```
http://localhost:5000/v2/
```
<img width="284" alt="image" src="https://github.com/user-attachments/assets/1a401114-e113-4a37-807b-344c47a98dbd">

  
  

  
  
 
  
