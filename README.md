# Microservices-Task

## Overview
This document provides details on testing various services after running the `docker-compose` file. These services include User, Product, Order, and Gateway Services. Each service has its own endpoints for testing purposes.

---

## Docker file for each microservices

<img width="883" height="446" alt="image" src="https://github.com/user-attachments/assets/3bf537fc-d0f3-4746-b717-e9f43b8f1a28" />

## Docker compose for microservices and communication setup

<img width="945" height="317" alt="image" src="https://github.com/user-attachments/assets/6ae487da-e966-4e7b-a5f0-41f949681936" />

## Docker compose file code

<img width="1227" height="799" alt="image" src="https://github.com/user-attachments/assets/cc65c6ef-56d0-4585-bb40-1b213bcbc898" />

<img width="752" height="575" alt="image" src="https://github.com/user-attachments/assets/62c9ee17-ba7f-4b6e-9e4f-a920a6e9436c" />




## Services and Endpoints

### **User Service**
- **Base URL:** `http://localhost:3000`
- **Endpoints:**
  - **List Users:**  
    ```
    curl http://localhost:3000/users
    ```
    Or open in your browser: [http://localhost:3000/users](http://localhost:3000/users)

    <img width="902" height="184" alt="image" src="https://github.com/user-attachments/assets/75bd6173-aeae-42e0-9891-468d77de44be" />


---

### **Product Service**
- **Base URL:** `http://localhost:3001`
- **Endpoints:**
  - **List Products:**  
    ```
    curl http://localhost:3001/products
    ```
    Or open in your browser: [http://localhost:3001/products](http://localhost:3001/products)
<img width="982" height="263" alt="image" src="https://github.com/user-attachments/assets/d3b7a477-a6ca-4222-861b-c36828c5bfeb" />

---

### **Order Service**
- **Base URL:** `http://localhost:3002`
- **Endpoints:**
  - **List Orders:**  
    ```
    curl http://localhost:3002/orders
    ```
    Or open in your browser: [http://localhost:3002/orders](http://localhost:3002/orders)
<img width="1896" height="425" alt="image" src="https://github.com/user-attachments/assets/94be958a-34e7-4be7-be65-692d784d43f4" />

---

### **Gateway Service**
- **Base URL:** `http://localhost:3003/api`
- **Endpoints:**
  - **Users:**  
    ```
    curl http://localhost:3003/api/users

    <img width="1847" height="316" alt="image" src="https://github.com/user-attachments/assets/32589a7d-e68e-4f24-ab16-18e21a2e37d1" />

    ```
  - **Products:**  
    ```
    curl http://localhost:3003/api/products

    <img width="1798" height="328" alt="image" src="https://github.com/user-attachments/assets/4e1cc813-e0d6-40bd-96a2-1512769caff7" />

    ```
  - **Orders:**  
    ```
    curl http://localhost:3003/api/orders

    <img width="1906" height="370" alt="image" src="https://github.com/user-attachments/assets/abf8b266-c5b7-41f7-8125-80a5f4f053bd" />

    ```

---

## Instructions
1. Start all services using the `docker-compose` file:
   <img width="1894" height="260" alt="image" src="https://github.com/user-attachments/assets/39bb5ac1-ec2c-46d5-a364-365774f44f78" />

   ```
   docker-compose up

   <img width="1167" height="400" alt="image" src="https://github.com/user-attachments/assets/62851078-2652-4639-8555-be610c52c56d" />

   ```
   
3. Once the services are running, use the above endpoints to verify the functionality.

Happy testing!
