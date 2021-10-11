# AWS-SageMaker
I have followed the below steps for creating my first notebook instance with AWS SageMaker:

### 1. After creating a free tier account in AWS, search "SageMaker" in the search bar.
![image](https://user-images.githubusercontent.com/75041273/136743250-3f89e2d3-55a8-4126-bcfa-67c2983f31cc.png)

### 2. Click on "Notebook Instances".
![image](https://user-images.githubusercontent.com/75041273/136743454-cf4ab875-65d1-445d-8f29-fd57f05004f5.png)

### 3. Select "Create Notebook Instance".
![image](https://user-images.githubusercontent.com/75041273/136743624-be852a4c-1ced-4b08-8c55-999bfeeaba95.png)

### 4. Give the "Notebook instance name" and for the "Notebook instance type" select either "t2" or "t3". I have selected "ml.t2.medium".
![image](https://user-images.githubusercontent.com/75041273/136744263-7fce9ebb-65ec-47e0-b5d7-d2b2d90be158.png)

### 5. Under "Permissions and encryption" select "Create a new role".
![image](https://user-images.githubusercontent.com/75041273/136744461-f1e4f177-c848-440a-b1e9-2f220a58963f.png)

### 6. Select "Any S3 bucket" as I don't want any specific S3 bucket exclusively for this instance and then click on "Create role".
![image](https://user-images.githubusercontent.com/75041273/136744568-2fb6b270-0551-4339-8e2b-1e913c8ef3bc.png)

### 7. Then select "Create notebook instance".
![image](https://user-images.githubusercontent.com/75041273/136744889-a35cadf3-9cd8-470e-924e-a4ea252ba653.png)

### 8. After 2-3 minutes the new notebook instance will be created. Under "Actions" select "Open Jupyter".
![image](https://user-images.githubusercontent.com/75041273/136746153-c1c66859-97cb-4ef2-929c-2720cbd395af.png)

### 9. A jupyter instance just like our local jupyter notebook homapage will open. Select "New" and click "conda_python3" as I want to build a Machine Learning model.
![image](https://user-images.githubusercontent.com/75041273/136746456-60bf7a3b-3018-4a32-a8d7-6a94b49c1455.png)

### 10. Now, we are good to go!
![image](https://user-images.githubusercontent.com/75041273/136746613-6eb642d7-9f43-43d5-9f16-183e9c0b45c4.png)

## Creating a s3 bucket
I have followed the below steps for creating my first s3 bucket:
### 1. Search "s3"
![image](https://user-images.githubusercontent.com/75041273/136767651-9b2fed10-43c9-48e9-b9b5-1823b059da2e.png)

### 2. Click "Create bucket".
![image](https://user-images.githubusercontent.com/75041273/136767869-ae40b1cd-6da1-4996-8163-adb511a1c58b.png)

### 3. Give the bucket name.
![image](https://user-images.githubusercontent.com/75041273/136767232-c7b66d4a-e054-4340-8bab-ee78018a5614.png)

### 4. Enable the Bucket Versioning as this will save multiple actions based on time stamps and will reduce error or mistakes.
![image](https://user-images.githubusercontent.com/75041273/136768413-6a36929e-5d77-4a6a-8c81-6255a6213de8.png)

### 5. Click "Create bucket".
![image](https://user-images.githubusercontent.com/75041273/136768625-b23e1bdf-ae71-4de5-9e21-99457dcee368.png)

### 6. In order to access the s3 bucket created from our jupyter notebook, go to search bar and type "IAM" and click "IAM".
![image](https://user-images.githubusercontent.com/75041273/136769060-3df7f67c-26fe-4f74-bced-cbe070ccd8dc.png)

### 7. Select "Users" from the side bar.
![image](https://user-images.githubusercontent.com/75041273/136769293-5d4d22ef-0663-43c9-a656-30d26ce4e751.png)


### 8. Select "Add users"
![image](https://user-images.githubusercontent.com/75041273/136769452-88f2405e-d980-45b5-a55c-22d6d3265a8b.png)

### 9. Create a "User name" and check the "Access key - Programmatic access"
![image](https://user-images.githubusercontent.com/75041273/136769807-9bed8c18-9729-4ed1-98ed-4ec5895afd73.png)

### 10. Select "Attach existing policies directly"  then check "AmazonS3FullAccess" and then click "Next:Tags".
![image](https://user-images.githubusercontent.com/75041273/136770443-23b232e8-bfac-43be-ad7d-7d482a5b3328.png)

### 11. No need to give key and value pairs so click "Next:Review"
![image](https://user-images.githubusercontent.com/75041273/136770703-6d989efe-7310-4d5f-b562-7ebd07111fd5.png)

### 12. Click "Create user"
![image](https://user-images.githubusercontent.com/75041273/136770872-effcbad0-f04a-4c7e-b4e1-d72f96d9e127.png)

### 13. Download the csv file to get the access key and the secret access key. 
![image](https://user-images.githubusercontent.com/75041273/136771056-ff66a958-2bf6-44b0-819f-1b527e457c5b.png)




