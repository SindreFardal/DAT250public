
# DAT250 - Assignment 3


## screenshot of validation
![image](https://user-images.githubusercontent.com/50116138/133889450-b3b32734-d8c4-4484-b1fd-5b134c08eb97.png)


## Experiment 1 MongoDB CRUD operations

### InsertMany screenshot
![image](https://user-images.githubusercontent.com/50116138/133890349-d8bab4d2-bab2-4db3-a375-19bd69fc58b9.png)

### query screenshot (Specify equality condition)
![image](https://user-images.githubusercontent.com/50116138/133890470-f5487a34-0770-4eb1-a733-8d91dd8f79ae.png)

### Update screenshot
![image](https://user-images.githubusercontent.com/50116138/133890671-8a13ed52-3124-49a2-8a45-4b58e3da5694.png)

### Delete screenshot
![image](https://user-images.githubusercontent.com/50116138/133890721-6b3f6986-47ad-4b86-a24a-bc7c72d6f34a.png)

### Bulk write screenshot
![image](https://user-images.githubusercontent.com/50116138/133890787-1c14e809-994d-44d4-ac46-0c4bfbb441cd.png)

## Experiment 2 Aggregation

### Total price per customer screenshot
![image](https://user-images.githubusercontent.com/50116138/133891214-d1959c6c-7c1f-4e06-955f-52ed3bed8ccf.png)

### Calculate Order and Total Quantity with Average Quantity Per Item Screenshot
![image](https://user-images.githubusercontent.com/50116138/133891314-d5c483c7-7667-453d-aae9-2376bcec7b9d.png)

### Screenshots of the additional operation
#### The creation of the map function and the reduce function
![image](https://user-images.githubusercontent.com/50116138/133892086-cefa1752-c6bb-48af-8311-b10b0f3f6a8f.png)

#### Screenshot of the map reduce function
![image](https://user-images.githubusercontent.com/50116138/133892138-e644689a-cf4b-4a5c-8cd0-e1a052730859.png)

I realised when trying to call this function that when i defined the function i used a name with a space in it, which doesn't work.
![image](https://user-images.githubusercontent.com/50116138/133892219-3bbc2dc5-67cc-435d-ac8a-3544e10ce3a5.png)
So i had to make it again, this time with one text containing no spaces.
![image](https://user-images.githubusercontent.com/50116138/133892277-245d87ce-bed1-426a-b6af-38843c244f6a.png)

Screenshot of the result:
![image](https://user-images.githubusercontent.com/50116138/133892293-a8d92262-5866-485f-82aa-89f9169a0719.png)




## Technical problems
I didn't encounter many problems/difficulties but one i did encounter was when trying to install MongoDB was "Failed to add user to group. <some numbers> SINDRE-PC Performance Monitor Users". I solved this by typing "net localgroup "Performance Monitor Users" /add" into cmd, and i was good to go.
