# CORS_Policy_Demo_Code

## Uploaded the index.html and image.jpeg to the bucket in mumbai region and make bucket and objects public
![image](https://user-images.githubusercontent.com/65528935/118406303-1e53ec00-b699-11eb-8de9-87a762af26f2.png)

## Uploaded the extra.html to the bucket in singapur region and make bucket and objects public
![image](https://user-images.githubusercontent.com/65528935/118406330-3b88ba80-b699-11eb-877d-abc57269cfbc.png)

The extra.html is the html page whose data we want to sync in the index.html so we will give its endpoint url to the fetch function by replacing cross_region_bucket_url.
* Copy the url as below.
![image](https://user-images.githubusercontent.com/65528935/118406678-6fb0ab00-b69a-11eb-9e66-8395588c9539.png)
* Now copy the url of the index.html as below.
![image](https://user-images.githubusercontent.com/65528935/118406411-9ae6ca80-b699-11eb-957b-6d3ffa8f4e19.png)

You will see the following output:
![image](https://user-images.githubusercontent.com/65528935/118406913-c2d72d80-b69b-11eb-96a0-2edc1c90000d.png)

You will see  **hi extra** not appear in tha page.

Region is CORS policy as shown below:
![image](https://user-images.githubusercontent.com/65528935/118407033-5f013480-b69c-11eb-9d78-bf841e6fc115.png)

CORS policy is implement by browser if the domain don't allow access to its resources from other origin.

Enabling Cross-Origin Resource Sharing  in the singapur bucket by configuring it with CORS.json. You will see the following ouput.
![image](https://user-images.githubusercontent.com/65528935/118407498-a2f53900-b69e-11eb-8ed1-5a468c92f7d2.png)








