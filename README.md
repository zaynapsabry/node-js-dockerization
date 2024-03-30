# Node-js-dockerization
Containerize TO-DO App
It is a dockerization for a simple TO-DO list app in node.js.

## Installation ⬇️
To run this project locally, follow these steps:


1. **Clone the repository:**

    ```bash
    git clone https://github.com/zaynapsabry/node-js-dockerization.git
    ```
2. **Run this command to install all dependencies:**
   
  ```bash
  npm install
  ```

3. **To Build image from Dockerfile run:**
 
  ```bash
  run docker build -t <node_image_name> command
  ```

4. **To create a bridge network run:**

  ```bash
  docker network create <network_name> command
  ```

5. **Run a node container:**
   
  ```bash
  run docker run --name <container_name> --network <network_name> <node_image_name>
  ```

6. **Run a mongo container:**
   
  ```bash
  run docker run --name <container_name> --network <network_name> mongo 
  ```
