#Cody's First Blog

![image](https://github.com/user-attachments/assets/2c52691b-07fd-4208-95c0-215290e49216)

## Flag 1:

    As it mentioned PHP, let's test PHP code in comments

    <?php echo "test"
    
![image (1)](https://github.com/user-attachments/assets/33beb0c3-b910-4cf8-8216-3df2f477b9cb)

## Flag 2:

If we inspect the page source, we can see admin page commented out.

![image](https://github.com/user-attachments/assets/c31be519-4582-4ea2-b563-a8200c1c71de)

Uncomment it and access the admin login page

![image](https://github.com/user-attachments/assets/a8ca95a9-1cee-4ddb-83d6-2d844227fae3)

We can the POST request of `admin.auth.inc` looking for authentication. Thus, remove `auth` and access the page through `admin.inc`

![image](https://github.com/user-attachments/assets/8b1ec6b7-9bdb-43c2-b9ca-cbbe328245a8)

![image (2)](https://github.com/user-attachments/assets/95423581-fe66-4101-ab7c-6ac252db6a91)

## Flag 3:

We can see its mentioned there that it can accept file uploads only by the author which is `localhost` .

Thus, access the page by giving `?page=http://localhost/index`

![image](https://github.com/user-attachments/assets/186b66ee-30eb-45d3-a856-63c4c061ec44)

In page source, we can see the flag.

![image (3)](https://github.com/user-attachments/assets/7c212a21-a36d-4b44-8e1c-52c2132726e0)
