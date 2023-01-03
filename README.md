# Amazon-Food-reviews-sentiment-Analysis
Here Amazon food reviews data is analysed using  used to classify the sentiment  of the review given by the Amazon user.

Steps:
1. Build a model on your local box (Amazon Fine Food reviews) and store the model and
other key model related variables in .pkl files
2. Launch a micro instance on AWS.
3. Connect to the AWS box [ssh]
4. Move the files to an AWS EC2 instance/box [scp]
5. Install all packages needed on the AWS box.
6. Run app.py on the AWS box.
7. Check the output in the browser.

[2] Launch a micro instance on AWS.
Creating an instance:
1. Create an AWS account https://aws.amazon.com,
https://portal.aws.amazon.com/billing/signup#/start
2. Login: https://console.aws.amazon.com
After login:
Launch the EC2 instance
3. Choose the ubuntu free tire
Click on select

4. Choose t2.micro free tier eligible
Click on review and launch

5.Click on launch
6.Click on “Download Key Pair” and save the .pem file then click on “Launch Instance”

7.You will see this screen, you have successfully launched the an EC2 instance, now we need to
launch an flask api in it

8. Final step:
Select the “Network & security” -> Security groups and then click “Create Security Group”
Then add the specific security group to network interface

[3] Connect to the AWS box and Move the files to an AWS EC2 instance/box []

![image](https://user-images.githubusercontent.com/69012134/210358550-89f02da8-ec41-440a-839b-b1e1ad33e645.png)

[4] Run app.py on the AWS box and check the output in the browser.

![image](https://user-images.githubusercontent.com/69012134/210357703-afb2f63b-d47b-452e-ab9a-aae662a263fd.png)


![image](https://user-images.githubusercontent.com/69012134/210357484-01e99b90-550b-4040-be13-eaf420ecfc52.png)

![image](https://user-images.githubusercontent.com/69012134/210358811-f2246305-9ac8-4c55-a8a7-ddad0b594c2f.png)

![image](https://user-images.githubusercontent.com/69012134/210358872-a122e4f6-22c0-4eb6-9cb7-8f8f7952a572.png)


