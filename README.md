# TestMicroservice

This project demonstrate employee database using ArrayList to Insert Data, Delete Data, Get All Record From Employee List.

Step1 : Run the application using Eclipse or STS

![Screenshot from 2024-01-09 22-46-46](https://github.com/Sharathrao-Appmod/Assignment-Testmicroservice/assets/155999647/d243237d-f665-4952-8e7c-b3f2c8683e74)

Step2 : Open Postman 
Step3 : Add HOST ENDPOINT: http://localhost:8080/employees REQUEST METHOD : GET (to show all records)

![Screenshot from 2024-01-09 22-45-40](https://github.com/Sharathrao-Appmod/Assignment-Testmicroservice/assets/155999647/6146ff7c-0308-471d-b1e4-45906ee3d6a1)


        Add HOST ENDPOINT: http://localhost:8080/employee METHOD: POST 
        RequestBody: 
        {
             "id": "S105",
             "name": "Norton",
             "department": "Support",
             "dateOfJoining": "15-09-2022"
        }
        
        ResponseBody: 
        
      [
       {
        "responseCode": "200",
        "responseStatus": "RECORD INSERTED"
       }
      ]    
      
![Screenshot from 2024-01-09 22-48-31](https://github.com/Sharathrao-Appmod/Assignment-Testmicroservice/assets/155999647/43ee37a7-82e4-489b-b22b-02bcc0aa1c2f)

     
      ADD HOST ENDPOINT: http://localhost:8080/employer METHOD : POST
      RequestBody: 
        {
            "id": "S105"
        }
        
      ResponseBody: 
      [
        {
           "responseCode": "200",
           "responseStatus": "RECORD NOT FOUND"
        },
       {
           "responseCode": "200",
           "responseStatus": "RECORD NOT FOUND"
        }
    ]

![Screenshot from 2024-01-09 22-50-36](https://github.com/Sharathrao-Appmod/Assignment-Testmicroservice/assets/155999647/f1915d3b-a0c7-4e88-ad2b-36d2a171f6e3)

    
    
