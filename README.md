# Serverless-project-using-DynamoDb-lambda-data-encryption

### 1-Create DynamoDB Table People and create item

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/85665394-5e5f-4d5e-8940-0a7ea3ce46cd)

### Below is a "PersonRecords" table with primary key as "PersonID" (unique identifier).

// first person

{
    "LastName": "Smith",
    "FirstName": "Fred",
    "PersonID": 1,
    "Phone": "700-123-4456"
}

// Second person

{
 "FirstName": "Jan",
 "LastName": "Smith",
  "PersonID": 2,
 "Phone": "700-123-4456",
 "Address": {
  "City": "London",
  "Country": "England",
  "Street": "123 Baker road"
 }
}

// Third person

{
 "PersonID": 3,
 "Address": {
  "City": "London",
  "Country": "England",
  "Street": "123 Baker road"
 },
 "FirstName": "Scott",
 "LastName": "Smith",
 "Phone": "700-123-4456"
}


### 2-Insertting into DynamoDB using lambda function

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/3622a96f-ff8b-4b3c-8337-7e8f8cb2bba9)

### 3-Deletting in DynamoDB using lambda function

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/b0d5a26b-3096-478e-bb87-97276b15ce97)

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/4ea8f5a7-9bea-42f9-8dbe-2e961ff0b9fc)

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/43ed2a42-3066-40c0-befa-6ae366581c5c)

### 4-DynamoDB Strongly and Consistent Read

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/a50caa1d-9706-4127-9957-8ac2bb6bcef3)

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/70178c2c-3caa-46a9-892a-887e0da5d922)

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/9a38c895-05fb-4e5d-b891-0f492086bc6e)

### 5-DynamoDB Secondary index

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/a9218495-c2ca-4fa7-ad60-c6ffa1b6caaa)

// Create item

{
 "Artist": "No one you know",
 "SongTitle": "My dog spot",
 "AlbumTitle": "Hey now",
 "Genre": "Country",
 "Price": 1.98,
 "YearOfAlbum": "1083"
}

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/0360e981-365d-4fbc-bf9f-518fe219229b)

### 6-Encryption of Data using Cmk in lambda

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/f3a18bd3-2092-4510-b003-c5f3da213caa)

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/4b43f5a2-85e3-4a73-8750-7de020db9c94)

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/17e1718b-f890-4a6f-8948-21a3a928d437)

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/f00994b5-8af5-48c3-b25a-2c2ae4d797d5)

















