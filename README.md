# Brute Force Attack using Burpsuite


Name: Rory Stiff

Disclaimer: This is for educational purposes only.


Description: 


I will be showing how to brute force attack a web application registartion form page. 
To do this project im using burpsuite and im using bwapp wich is a application within the OWASP
system that allows us as pen testers to be able to train on there.




![image](https://github.com/user-attachments/assets/0df5ff07-3467-408c-8bb2-84ab06bf4e18)






Outline



-> Brute Force Attack


-> Burp suite


-> How to use Burp suite to brute force a login page



-> Brute force attack mitigation









Brute Force Attack




A brute force attack is a technique used by hackers to get into someone's account guessing
their login credintials. The hacker essentially attempts various usernames and passwords until
they manage to find the correct login information.




![image](https://github.com/user-attachments/assets/02407853-2ec6-4856-811b-b5e92d408eb7)







Burp suite




Burp suite works as an interception proxy between the browser and the server. So when you
make a request from the browser, it gose to the burp proxy then the server. The proxy can 
intercept web request and read and edit those request.





![image](https://github.com/user-attachments/assets/93e58b27-141f-4839-a927-74fc8d0563f0)






How to use Burp suite to brute force a login page


First is to turn the interception on in the proxy tab in burpsuite. Then
I will use foxy proxy to listen to the traffic with specified port.





![image](https://github.com/user-attachments/assets/063915d6-edda-4b74-b5f8-275ef2f93c10)







![image](https://github.com/user-attachments/assets/4d1db45b-9279-48a3-acea-634884190778)






The next thing to do is now send the tarffic to the intruder and in the intruder tab
I will clear the hole payload first then I will add the password field to the payload.




![image](https://github.com/user-attachments/assets/e83a02a5-3057-4f1d-8521-dca718510827)








Next is to add a simple password and also take the error message when someone enetrs in
a wrong username or password, list like this...




![image](https://github.com/user-attachments/assets/ca34d091-177d-497d-a914-fd2d23fbe6c8)





![image](https://github.com/user-attachments/assets/3b34a74c-8105-43fd-8eeb-59d98114bcb7)






![image](https://github.com/user-attachments/assets/a0468b79-f5ff-4950-a095-433b2dbb5e9c)













































