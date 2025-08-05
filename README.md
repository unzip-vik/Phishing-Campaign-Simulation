# Phishing Campaign Simulation

## Objective

The purpose of this project is to raise awareness about phishing attacks and to help individuals understand how to recognize and avoid them. Phishing is one of the most common cyber threats, and it relies on social engineering to trick users into revealing sensitive information such as passwords, financial data, or personal details.</br></br>By simulating a phishing campaign, the project allows participants to experience real-world scenarios in a safe and controlled environment, without any risk of actual harm.

## What I Learned From This Project

- How phishing attacks operate in a real-world context.
- How users interact with suspicious emails.
- The importance of continuous education and awareness programs to reduce the risk of successful attacks.

## Tools Used

- Zphisher for generating a fake website template.
- Cloudfared, a port forwarding service used with Zphisher to host the website.
- SET toolkit for distributing mails.


## Steps
- Step 1. Create an e-mail target list.
<img width="937" height="800" alt="1 - Copy" src="https://github.com/user-attachments/assets/8336a25f-60a2-443b-83a1-b3578115aa23" /></br>
- Step 2. Launch Zphisher and choose an attack option. For this example I chose the instagram login page. 
<img width="966" height="694" alt="3" src="https://github.com/user-attachments/assets/3c3415c2-b09c-4f21-b663-14d13151e515" /></br>
- Step 3. Choose a port forwarding service. I recommend Cloudfared as it has worked the best out of the other two options.
<img width="966" height="694" alt="4" src="https://github.com/user-attachments/assets/f25c2c27-1113-44f9-bb4c-0e17a67d8ca0" /></br>
- We have a fake website up and running!
<img width="966" height="694" alt="6" src="https://github.com/user-attachments/assets/eea684a8-4719-4f88-8d09-64bda4fb0317" /></br>
- Website preview:
<img width="1355" height="977" alt="7" src="https://github.com/user-attachments/assets/9077291b-40e2-4b3d-816c-2e7bf1eb9578" /></br>
- Step 4. Launch SET toolkit and choose the first attack option from the menu.
<img width="966" height="694" alt="8" src="https://github.com/user-attachments/assets/79f04bd9-f46f-4bbf-9086-2cae48b38bed" /></br>
- Step 5. Select the mass mailer attack as we have to distribute the phishing e-mails to multiple targets.
<img width="966" height="694" alt="10" src="https://github.com/user-attachments/assets/f7191f5b-b394-45a9-a62f-489a5d280568" /></br>
- Step 6. Edit the subject of the mail and input the body of the e-mail as html or plain. For this example I imported an html code that resembles a security update which needs a re-login (you can also use their pre-made mail templates).
<img width="966" height="694" alt="13" src="https://github.com/user-attachments/assets/974b583f-5922-4cee-97b5-d5b01a42d27d" /></br>
- Step 7. Import the .txt list of targets and login with a gmail account that will distribute the e-mails (note that in order to login from a third party application, you need to enable the 2FA option in your gmail account. Once that is enabled, a new password will be generated for the third party login).
<img width="966" height="694" alt="16" src="https://github.com/user-attachments/assets/6032cc09-6049-4878-ab42-448a66005659" /></br>
- Mail preview:
<img width="1355" height="977" alt="17" src="https://github.com/user-attachments/assets/79fff5e0-e8cf-4b06-b40e-af06d22e86c8" /></br>
- Step 8. Locate the Zphisher folder. You will find two files, ip and usernames. The text files contain the information that is gathered from targets falling for the phishing attack.
<img width="1026" height="803" alt="18" src="https://github.com/user-attachments/assets/6568c406-4c9a-4f6a-be24-8f1cb4ebdadf" /></br>
- Step 9. Review the logs. The "ip.txt" contains ip, browser and OS information, while the "usernames.dat" will contain the information that was input in the login boxes.</br></br>
<img width="1920" height="726" alt="19" src="https://github.com/user-attachments/assets/63a62718-44f4-4d9a-bf72-6fd14197fee0" /></br>

## Conclusion

The results highlighted the critical importance of cybersecurity awareness. Even a realistic but harmless phishing attempt can capture the attention of unsuspecting users, proving that human error remains one of the biggest vulnerabilities in any organization’s security posture.
