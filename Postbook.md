# Postbook

![image](https://github.com/user-attachments/assets/507fe0b5-e0b6-4d54-bb38-b2e51ff375ea)

## Flag 1

    We got a default username as a hint, which is : "user" and have to guess its password. Through turbo intruder we got the password.

![image](https://github.com/user-attachments/assets/96ed1596-0515-44b0-9acd-5c66f69f9fdc)

![Screenshot 2024-08-21 121056](https://github.com/user-attachments/assets/feb3e9b4-21e9-4378-afa8-f950263e6c66)

## Flag 2

    Create a post and we can see id number in the URL. Try changing it.
    
![Screenshot 2024-08-21 123604 (1)](https://github.com/user-attachments/assets/eed3f24e-1034-4190-9ee2-13a1b9093230)

![Screenshot 2024-08-21 124025](https://github.com/user-attachments/assets/64fc5122-c698-46ad-a635-d7771ef49c15)

## Flag 3

    Inspect the form of creating a post
    
![image](https://github.com/user-attachments/assets/348e617e-93c3-4825-8904-a6b5d057f37e)

    A hidden input. Remove the hidden to enable it

![image](https://github.com/user-attachments/assets/e00deb5a-2fe1-4ace-9330-880ce62a946a)

    Chnage the input value and create a post.

![image](https://github.com/user-attachments/assets/fbc0e6e5-6cec-40db-a88e-3f092d1bf4cf)

## Flag 4

    We got a post with id=3 in URL. Try changing it
    
![image](https://github.com/user-attachments/assets/42639eaa-b8b8-4150-95f7-7e1ef33c3550)

    We got a hint of 189*5 which equals 945

![image (1)](https://github.com/user-attachments/assets/ff502301-fa8e-450f-829f-f946a68ba40f)

## Flag 5

    Let's check whether we can change others posts. First go to edit our post and find other user's post through changing the id num in the URL.

![image](https://github.com/user-attachments/assets/3d4d267d-703f-4e57-9706-074d21b7d92a)

    Now edit the post and click save
    
![image (2)](https://github.com/user-attachments/assets/9903b337-6259-488e-9a36-d0ff2425c2b1)

## Flag 6

    Cookies allows us to stay signed in. Try Cookie hijacking

![image](https://github.com/user-attachments/assets/57897563-5cd7-46f1-9ebf-995ee6802a32)

    We got the cookie value and check by reversing the hash

![image](https://github.com/user-attachments/assets/e6ebdc88-b815-4255-84b6-8fa31e67d9dc)

    We got hash equivalent of 2 which is the id num. Now, create the hash for id num 1 and pass it as cookie value.

![image](https://github.com/user-attachments/assets/19e5fbb4-6603-45da-a471-b6a486815e38)

![image](https://github.com/user-attachments/assets/6c09491c-f904-4dac-b60c-0eae7c9d8066)

![image (3)](https://github.com/user-attachments/assets/1c7870b7-b780-4f24-9bff-e50cf1c4423c)

## Flag 7

    We have to inspect the delete element where it consists of a ID

![image](https://github.com/user-attachments/assets/e63054cd-681b-4bb9-9ed1-42d7e199a34c)

![image](https://github.com/user-attachments/assets/17d38f7c-5d97-4d0c-8c6d-f02235574737)

    It has a hash equivalent of id=2. Change it to other id equivalent hash. For ex, id-3

![image](https://github.com/user-attachments/assets/11799f26-3dad-45ba-b634-b33e571c66dc)



