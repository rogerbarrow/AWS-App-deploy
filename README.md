# Deploying a Node Js Application on AWS EC2
### Step 1 Testing the project locally
![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/37bc7c76-796b-46bf-897a-8c2ec637efb8)
* ![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/d1b2c4f6-030c-4267-bd47-7dbabadcb661)

1. Clone this project
```
git clone https://github.com/roger/AWS-App-deploy.git
```
2. Setup the following environment variables - `(.env)` file
```
DOMAIN= ""
PORT=3000
STATIC_DIR="./client"

PUBLISHABLE_KEY=""
SECRET_KEY=""
```
  * because this is a JavaScript App we will require a  .env file
  * ![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/446633f1-b343-442b-b933-0bc37cc360c2)
 *![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/d0c0a0de-9c67-4b4a-873d-05d71c3c9d18)
 *![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/f1db8d0f-8878-42e9-99ee-4afc3ab5fa69)
* ![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/9aeb0fe3-3eea-4dff-92e5-0a844e4f840c)

# Step 2 go to local host:3000 to verify App is running
 *![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/6a6a9d9f-9975-415a-9931-7cea22c43736)

# Step 3 Create a EC2 Instance in AWS
![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/0a782b4d-d2c6-4cd6-9ee9-bf11d1789f5b)
 * Login to your instance I will be SSH into the Instance
 * ![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/c9bef1e4-4feb-43ae-ac78-a39d0d23e0d7)
 * ![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/9c707bd5-57e3-4472-b6d7-dae7a95a470b)
 * Congrat your Login in, Next lets update the package
 * ![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/25b8cfac-87b4-4d61-85f7-3c0dcafcd226)
 * download node.js
 * ![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/134b4016-07d6-42b0-93ea-5728da471d35)
* download npm
* ![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/f6630947-5445-4480-b70c-dd721db12509)
* Clone the Repo
* ![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/8d3d2809-2143-4c7c-8a33-0575bc2bc2a5)
![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/3e822d75-e861-41c7-a468-48a80b6f7804)
# Step 4 run npm install and npm run start
*![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/7c59b0e6-286a-4715-a8a6-57e6d085101c)

# Step 5 We need to expose Port 3000 in the Security Group to have access to the application
 *![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/7298b355-b278-4716-89c8-8e08b971bf61)
 * ![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/5457af03-9d6c-4919-9112-d9c1bdfdf666)

# Congrat your Application is running on AWS now
*![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/4fc311ed-de76-4763-8b83-87da474e9fbd)
 # Dont forget to Terminate the Instance
   ![image](https://github.com/rogerbarrow/AWS-App-deploy/assets/46138186/f2c41115-749f-45aa-9e58-2b6258857bc1)




