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



### 4. Leave the default settings at current settings. Validate public access is disabled, then click "Create Bucket"

![image](https://github.com/user-attachments/assets/95274119-965b-4e98-929d-29fa9323e837)




### 5. If you see the green "Successfully created bucket" banner on the top of your page, you are good to go!

![image](https://github.com/user-attachments/assets/a9657c4f-0c1e-47ff-b411-4e590662ac51)



### 6. Now you will create 3 Users, Head back to the "Console Home" and click "IAM" or search for "IAM" in the search bar. You will have zero Roles and Policies if this is your first time.

![image](https://github.com/user-attachments/assets/75bdb94e-600f-4533-a0aa-0cf7d09fc7cf)

![image](https://github.com/user-attachments/assets/4056ff41-e57a-43d6-9d87-394e60009968)



### 7. Click "users" on the left panel.

![image](https://github.com/user-attachments/assets/ad2d15a3-47a7-4a62-a5ec-da53fa4632ca)

![image](https://github.com/user-attachments/assets/59cd482c-3b44-4183-9ebf-4c17c55e7ccc)



### 8. Click "Create User" on the top right.

![image](https://github.com/user-attachments/assets/5941b2bb-24d8-45d6-842c-5ff7aa587821)

![image](https://github.com/user-attachments/assets/11d8086e-cd12-47ac-9d33-b1c8d3371be3)



### 9. Enter a "User name" for your first user, then check the box next to "Provide user access to the AWS Management Console".

![image](https://github.com/user-attachments/assets/40f626e1-bb78-4285-8fe6-07ce9c2fdde4)


### 10. Select:
  
   - Select "I want to create an IAM user.
   
   - Select Custom password.
   
   - Ensure the checkbox that is next to "Users must create a new password at the nest 
     sign-in" is checked.

![image](https://github.com/user-attachments/assets/9189018c-d06e-4981-95f7-1b65f8b710f7)




### 11. Click "Next".

![image](https://github.com/user-attachments/assets/5ce4d621-bef6-48cc-bc1f-adc130c45c44)

![image](https://github.com/user-attachments/assets/94ce4b20-433a-4d08-8311-14ad858dc1e4)



### 12. Setting Permissions is optiontional, scroll down and click "Create group"

![image](https://github.com/user-attachments/assets/7a99800d-305f-48eb-8568-3b09b6310daa)

![image](https://github.com/user-attachments/assets/ce479bfd-14c4-46fa-862d-3874182d253e)



### 13. Enter the first "User group name"

 - Name this group "Developers".

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
 
 - If you forgot the Password for the User, click "Show" under "Console password", it's 
   also in the downloaded file.

![image](https://github.com/user-attachments/assets/8944e738-caf6-4f4e-9167-65d52975bd27)




### 19. Click "Return to users list" to create another User and Group with no access to S3 Bucket.
        
- If you didn't choose to download the file you will recieve an alert message asking if you wish to continue.

-   Click "continue" if you wish to proceed without the file.

![image](https://github.com/user-attachments/assets/660656a6-4961-4e1b-bda7-2f3b12e6dfac)

![image](https://github.com/user-attachments/assets/6fbec376-a3f5-4fff-bf69-016693dae8c9)



### 20. Click "Create user" on the top right.

![image](https://github.com/user-attachments/assets/3133ecd1-4742-46fb-b6f6-53a5321ea225)

![image](https://github.com/user-attachments/assets/be443a7d-9f5a-4000-993d-8aab882d6d4f)



### 21. Enter a "User name", check the box that displays "Provide user access to the AWs 
###     "Management Console".

![image](https://github.com/user-attachments/assets/1a39753f-afb8-4be6-a924-51b4406194a5)



### 22. Select the same options as the last  user:

   - check the box next to "Provide user access to the AWs "Management Console".

   - Select "I want to create an IAM user".
   
   - Select "Custom password".
   
   - Ensure the checkbox that is next to "Users must create a new password at the next 
     sign-in" is checked.

![image](https://github.com/user-attachments/assets/d0bcf134-1e0d-45b0-b546-c51d26da1ff2)



### 23. Click "Next".

![image](https://github.com/user-attachments/assets/5ce4d621-bef6-48cc-bc1f-adc130c45c44)



### 24. Create a "Group" for your Second "User". 

![image](https://github.com/user-attachments/assets/bdbcef51-3f33-4f51-920d-501507fc27ae)




### 25. Enter the second "User group name".

 - Name this group "Testers".

 - This time you will not add any "Permission policies".

 - Click "Create user group"

![image](https://github.com/user-attachments/assets/d7307a59-2639-4ebd-af53-00c7cd256a33)

![image](https://github.com/user-attachments/assets/67f81766-ecb3-4730-8376-5b914045b69a)




### 26. If creating the "Group" was successfull, you will notice a green banner on top of the page, then click "Next".
       
![image](https://github.com/user-attachments/assets/f952185f-08b2-4dc4-8639-cb36bbe7874c)

![image](https://github.com/user-attachments/assets/b5a652c0-c32a-4745-822d-3ccab8dbf025)



### 27. Review "User details", "Permissions summary", and etc....
 - Click "Create user" after correct info is validated.

![image](https://github.com/user-attachments/assets/6b54ed33-c54b-4834-9998-0ecb53aed044)

![image](https://github.com/user-attachments/assets/c72a9d8c-915c-49d2-8ec3-f71906e1876e)




### 28. You will recieve a green banner above if user was created succefully.
 
 - Download file if you'd like to see instructions for signing in.

 - Copy the URL displayed, you will need if for your User to sign in.
 
 - If you forgot the Password for the User, click "Show" under "Console password", it's 
   also in the downloaded file.

![image](https://github.com/user-attachments/assets/49b9fae1-91e3-4ef1-b3f5-87bb90865b9e)



### 29. Click "Return to users list" to create another User and Group with Administrator Access Programmitic
        
- If you didn't choose to download the file you will recieve an alert message asking if you wish to continue.

-   Click "continue" if you wish to proceed without the file.

![image](https://github.com/user-attachments/assets/efd116b5-08ae-4713-8f32-557467cad646)

![image](https://github.com/user-attachments/assets/7fc9d8a2-0c3d-4667-a53b-4fd096e0b2ba)



### 30. Now you will create your final "User" with "Administrator" access.  

 - You will also give "Programmatic" access to utilize CLI, SDKs, or APIs instead of the 
   web console. 

 - Click "Create user" on the top right.

![image](https://github.com/user-attachments/assets/4b525709-0228-40f5-ac5d-f0df89203d54)

![image](https://github.com/user-attachments/assets/63e7e57a-dea1-465a-a47d-733921269829)




### 31. Enter a "User name".

![image](https://github.com/user-attachments/assets/ab9a5d74-b1f0-4bc6-8656-6303b0f93308)





### 32. Take note of this message below. To give "Programmatic" access, you will need to add it after your new "User" and "Group" is created. 

![image](https://github.com/user-attachments/assets/9e1f0397-9494-44c7-b7c8-69f47165be49)



### 33. Select the same options as the last user:

 - check the box next to "Provide user access to the AWs "Management Console".

 - Select "I want to create an IAM user".

 - Select "Custom password".

 - Ensure the checkbox that is next to "Users must create a new password at the next 
   sign-in" is checked.

![image](https://github.com/user-attachments/assets/0ca328bd-d290-43de-9bd2-a19263d58a54)




### 34. Click "next"

![image](https://github.com/user-attachments/assets/87288f8a-73d4-46dd-9b77-a3c06d92d888)




### 35. Click "Create Group" for your third "User" on the top right.

![image](https://github.com/user-attachments/assets/ae3a589f-9018-4a7c-b590-6eb2a4cfee8e)




### 36. Enter the third "User group name".
 
 - Name this group "Admins". 

 - This time you will add "AdministratorAccess".

 - Then click "Create user group"


![image](https://github.com/user-attachments/assets/1eb92493-bd37-4f42-9514-740b387f3624)


![image](https://github.com/user-attachments/assets/b2758cec-d76d-4428-9021-54800079f8af)


### 37. If creating the "Group" was successfull, you will notice a green banner on top of the page. Before you click "Next", validate attachments below.

 - Validate your TWO "Attached policies" so you can test the access later.

 - The "Admins" will have "AdminstratorAccess".
 
 - The "Developers" will have "AmazonS3FullAccess".
 
 - The "Testers" will show a blank space because there is no policies attached.

![image](https://github.com/user-attachments/assets/308ecb78-58d0-41a4-a1a1-26e066ac20dd)


   

### 38. Click "Next".

![image](https://github.com/user-attachments/assets/7babc72b-43b3-47f5-9181-ee8184f70db5)



### 39. Review "User details", "Permissions summary", and etc...

 - Click "Create user" after correct info is validated.

![image](https://github.com/user-attachments/assets/d9244a57-cb28-458c-a612-806d632cf47c)

![image](https://github.com/user-attachments/assets/c72a9d8c-915c-49d2-8ec3-f71906e1876e)



### 40. You will recieve a green banner above if user was created succefully.

 - Download file if you'd like to see instructions for signing in.

 - Copy the URL displayed, you will need if for your User to sign in.

 - If you forgot the Password for the User, click "Show" under "Console password", it's 
   also in the downloaded file.

![image](https://github.com/user-attachments/assets/9c67c70.-6bbe-4ceb-bc83-e99e7e22a552)




### 41. Click "Return to users list".

 - If you didn't choose to download the file you will recieve an alert message asking if 
   you wish to continue.

 - Click "continue" if you wish to proceed without the file.

![image](https://github.com/user-attachments/assets/efd116b5-08ae-4713-8f32-557467cad646)

![image](https://github.com/user-attachments/assets/7fc9d8a2-0c3d-4667-a53b-4fd096e0b2ba)




### 42. You will see some info about the 3 users you created. 

  - If you notice one of user's name is spelled wrong, you can select the user and click 
   "delete" on the top right. You'll have to create it again.

  - One of the user's depicted is incorrect so it will be corrected. 
 
 - If you'd like to see the most up to date info, click the refresh button before the 
   "Delete" and "Create user" button.

![image](https://github.com/user-attachments/assets/4135559c-4bd3-4130-92d7-433f63a905ff)


### 43. Take note that the "Password age" will be updated.

 - Here's a screenshot of what is looks like after 2 days.
 
 - Use the scroll bar below to view more info to the right.

![image](https://github.com/user-attachments/assets/e03ef49a-954b-4845-9c52-a09551240e65)

![image](https://github.com/user-attachments/assets/c631387f-029b-428a-bd09-f89b9f4410e8)

   
### 44. To add "Programmatic" access to the user in the "Admins" group, click on the Admin's name.

![image](https://github.com/user-attachments/assets/9c9993ba-af70-485f-b30d-4dad6415209d)



### 45. Click on the "Security credentials" tab.

![image](https://github.com/user-attachments/assets/ce865b48-a835-42ab-9de8-77faf3e62268)



### 46. Scroll down to "Access Keys", then click "Create access key".

![image](https://github.com/user-attachments/assets/a151111c-e3fa-4a67-8275-bc12398fafee)

![image](https://github.com/user-attachments/assets/b07213e6-f9b5-4ff8-8d97-0e500b18ac69)




### 47. Select "Command Line Interface (CLI)".

![image](https://github.com/user-attachments/assets/fdf19a07-6207-48e4-8ef7-f54b98bbe660)




### 48. Scroll down to the bottom and select the box next to "I understand the above recommendation and want to preceed to create an access key", if you understand.

 - Then click "Next".

![image](https://github.com/user-attachments/assets/44fe0947-3d4d-40c8-a018-c207c9a8dd29)



### 49. Test and User Permissions:

   - You will need to verify that users and groups can only access resources as defined in 
     their policies.
   
   - User in "Developers" Group will have access to S3 Bucket, but no access to Command Line 
     Interface.
   
   - User in "Testers" Group will not have access to anything, including the bucket created.
  
   - User in "Admins" Group will not have access to S3 Bucket, but will have access to the 
     Command Line Interface (CLI).

     

