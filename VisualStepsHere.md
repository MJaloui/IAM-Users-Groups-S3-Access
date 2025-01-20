![github-header-image (1)](https://github.com/user-attachments/assets/d4095b05-eda3-4e02-b072-e7a7071dbf5f)


&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

## **Steps:**



### 1. Create an AWS account if you don't have one, then login to AWS and click on "S3" in the console to create a bucket.

![image](https://github.com/user-attachments/assets/43030082-c98e-4ffd-9e60-f05d91208a84)

![image](https://github.com/user-attachments/assets/53627f51-527f-4c76-ad0b-a6fa024dac73)


### 2. Click "Create Bucket".

![image](https://github.com/user-attachments/assets/516a4afe-c09e-424e-902b-95d7443e1405)

![image](https://github.com/user-attachments/assets/ee81a9ae-f212-4da3-99bc-ba60b532a007)



### 3. Enter a "Bucket name". 

![image](https://github.com/user-attachments/assets/cae28df9-9625-4f54-8233-5638688bb647)



### 4. Leave the default settings at current settings. Validate public access is disabled, 
       then click "Create Bucket"

![image](https://github.com/user-attachments/assets/95274119-965b-4e98-929d-29fa9323e837)




### 5. If you see the green "Successfully created bucket" banner on the top of your page, you 
       are good to go!

![image](https://github.com/user-attachments/assets/a9657c4f-0c1e-47ff-b411-4e590662ac51)



### 6. Now you will create 3 Users, Head back to the "Console Home" and click "IAM" or search 
       for "IAM" in the search bar. You will have zero Roles and Policies if this is your 
       first time.

![image](https://github.com/user-attachments/assets/75bdb94e-600f-4533-a0aa-0cf7d09fc7cf)

![image](https://github.com/user-attachments/assets/4056ff41-e57a-43d6-9d87-394e60009968)



### 7. Click "users" on the left panel.

![image](https://github.com/user-attachments/assets/ad2d15a3-47a7-4a62-a5ec-da53fa4632ca)

![image](https://github.com/user-attachments/assets/59cd482c-3b44-4183-9ebf-4c17c55e7ccc)



### 8. Click "Create User" on the top right.

![image](https://github.com/user-attachments/assets/5941b2bb-24d8-45d6-842c-5ff7aa587821)

![image](https://github.com/user-attachments/assets/11d8086e-cd12-47ac-9d33-b1c8d3371be3)



### 9. Enter a "User name", then check the box next to "Provide user access to the AWS 
   Management Console".

![image](https://github.com/user-attachments/assets/40f626e1-bb78-4285-8fe6-07ce9c2fdde4)


### 10. Select:
  
   - Select "I want to create an IAM user.
   
   - Select Custom password.
   
   - Ensure the checkbox that is next to "Users must create a new password at the nest sign- 
     in" is checked.

![image](https://github.com/user-attachments/assets/9189018c-d06e-4981-95f7-1b65f8b710f7)




### 11. Click "Next".

![image](https://github.com/user-attachments/assets/5ce4d621-bef6-48cc-bc1f-adc130c45c44)

![image](https://github.com/user-attachments/assets/94ce4b20-433a-4d08-8311-14ad858dc1e4)



### 12. Setting Permissions is optiontional, scroll down and click "Create group"

![image](https://github.com/user-attachments/assets/7a99800d-305f-48eb-8568-3b09b6310daa)

![image](https://github.com/user-attachments/assets/ce479bfd-14c4-46fa-862d-3874182d253e)



### 13. Enter a "User group name"

![image](https://github.com/user-attachments/assets/c8376214-a16e-4743-a25d-ea468588be6b)




### 14. Select Permission policy for "AmazonS3FullAccess", use the search box to search "S3".

![image](https://github.com/user-attachments/assets/83ab2ba5-343f-4361-a3c3-c3d23e46984d)



### 15. Click "Create user group". If you see the green banner above, the group was created successfully.

![image](https://github.com/user-attachments/assets/38c478a6-37fe-4d08-a0f5-e2f39bfd2ac9)

![image](https://github.com/user-attachments/assets/740c9045-9a5e-4157-a23e-ee7afc13d34a)




### 16. Validate everything, then click "Next".

![image](https://github.com/user-attachments/assets/b8b0fa48-2f5c-4900-ab8c-474ea3e369f1)



### 17. Review all of your "User details", "Permissions summary", and etc... 
   
    - Click "Create User".

![image](https://github.com/user-attachments/assets/63642f13-cc5e-4d83-b296-99b972118ba2)


### 18. You will recieve a green banner above if user was created succefully.
 
 - Download file if you'd like to see instructions for signing in.

 - Copy the URL displayed, you will need if for your User to sign in.
 
 - If you forgot the Password for your User, click "Show" under "Console password", it's also 
   in the downloaded file.

![image](https://github.com/user-attachments/assets/536ae5af-913e-4e6a-b1e4-bd51a9ce1d44)



### 19. Click "Return to users list" to create another User and Group with no access to S3 
        Bucket.
        
        - If you didn't choose to download the file you will recieve an alert message asking 
          if you wish to continue. Click "continue" if you wish to proceed without the file.

![image](https://github.com/user-attachments/assets/660656a6-4961-4e1b-bda7-2f3b12e6dfac)

![image](https://github.com/user-attachments/assets/6fbec376-a3f5-4fff-bf69-016693dae8c9)



### 20. Click "Create user" on the top right.

![image](https://github.com/user-attachments/assets/3133ecd1-4742-46fb-b6f6-53a5321ea225)

![image](https://github.com/user-attachments/assets/be443a7d-9f5a-4000-993d-8aab882d6d4f)



### 21. Enter a "User name", check the box that displays "Provide user access to the AWs 
###     "Management Console".

![image](https://github.com/user-attachments/assets/1a39753f-afb8-4be6-a924-51b4406194a5)



### 22. Select the same options as the last last user:

   - check the box next to "Provide user access to the AWs "Management Console".

   - Select "I want to create an IAM user".
   
   - Select "Custom password".
   
   - Ensure the checkbox that is next to "Users must create a new password at the next sign- 
     in" is checked.




### 23. Click "Next".

![image](https://github.com/user-attachments/assets/5ce4d621-bef6-48cc-bc1f-adc130c45c44)



### 24. Create a group for your Second User,

![image](https://github.com/user-attachments/assets/70442291-9dc6-4119-9bb5-22e172e730a2)












5. Test Permissions:
   - Verify that users and groups can only access resources as defined in their policies.

