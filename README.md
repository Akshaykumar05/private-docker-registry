# private-docker-registry


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
  
  

  
  
 
  
