# Petshop Pro

![image](https://github.com/user-attachments/assets/06adb8d6-aef2-4e9c-9417-785d77746a77)

## Flag 1

![image](https://github.com/user-attachments/assets/709f857b-dc7d-4288-8e7e-90b7cff0cf4b)

    Intercept it with Burpsuite, Look for the cart value price.
    
![image](https://github.com/user-attachments/assets/958a1016-b4a8-4c77-b338-e4e7add701e8)

    Replace it with 0 and forward for free checkout.

![Screenshot 2024-08-19 105616](https://github.com/user-attachments/assets/95c634c9-598d-4cd7-9663-e51960295238)

## Flag 2

    Search for any login protocol either through pages or URL.

![image](https://github.com/user-attachments/assets/bb6e8203-858a-4b3b-aafe-7d5395ab467c)

    If we try to guess the credentials, it shows the message Invalid Username

![image](https://github.com/user-attachments/assets/fd0eff8d-257d-4500-8965-ac20817b0670)

    Now we need to bruteforce the Username through Turbo Intruder

![image](https://github.com/user-attachments/assets/04c7040c-d0d3-48bf-88b1-ef090af414a4)

Wordlist : https://github.com/danielmiessler/SecLists/blob/master/Usernames/Names/names.txt

    We got a username hit and have to guess its password.

![image](https://github.com/user-attachments/assets/d9f680ee-ca8c-45d6-857e-bf46a11f79d8)

    Now, bruteforce password

Wordlist : https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/10k-most-common.txt

