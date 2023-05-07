#  PollingSystemAPI 🦁
# 🔗Hosting Link👇
# 🌐Checkout the API []()
---
## Introduction : 🫵
                 Creating a Polling System API where anyone can create questions with options and also add votes to it. 
                 It is built using Express, Nodejs, MongoDB.

  ---      
 # Routes & URL 🛣️:
 
🟠 /questions/create

   To create a new question hit the following URL with a post request:
         
   [https://polling-system-api-517c.onrender.com/api/v1/questions/create](https://polling-system-api-517c.onrender.com/api/v1/questions/create)
   
   ---
🟠 /options/:id/create

   To create a new option for a question hit the following URL with a post request:
   
   [https://polling-system-api-517c.onrender.com/api/v1/questions/:idOfQuestion/options/create]()
   
   ---
🟠 /options/:id/addVote
    
   To increment the count of votes on an option, hit the following URL with a get request:
   
   [https://polling-system-api-517c.onrender.com/api/v1/options/:idOfOption/addVote]()
   
   ---
🟠 /questions/:id
    
   To view a question and it’s options, hit the following URL with a get request:
         
   [https://polling-system-api-517c.onrender.com/api/v1/questions/:idOfQuestion]()
   
   ---
🟠 /options/:id/delete

   To delete an option, hit the following URL with a delete request:
   
   [https://polling-system-api-517c.onrender.com/api/v1/options/:idOfOption/delete]()
   
   ---
🟠 /questions/:id/delete

   To delete a question, hit the following URL with a delete request:
   
   [https://polling-system-api-517c.onrender.com/api/v1/questions/:idOfQuestion/delete]()
 
---
# Getting Started With The Project🏃

  🟠Fork the Project in your Repository.
  ---
  🟠Clone the Forked Repository in your Local System.
  ---
  🟠Install & Configure - NodeJS, MongoDB, Robo3T, POSTMAN.
  ---
  🟠Run 'npm install' in GitBash Terminal
  --- 
  🟠Run 'npm start' in GitBash Terminal
  ---
  ---
  # Features 💡:
- Users can create questions (you can add as many questions as you want).
- Users can add options to a question.
- Users can add a vote to an option of question.
- Users can delete a question -> A question can't be deleted if one of it's options has votes.
- Users can delete an option -> An option can't be deleted if it has even one vote given to it.
- Users can view a question with it's options and all the votes given to it.
---
  # Tools Used 🛠️:
  
  <img width="100" height="100"        src="https://images.ctfassets.net/aq13lwl6616q/7cS8gBoWulxkWNWEm0FspJ/c7eb42dd82e27279307f8b9fc9b136fa/nodejs_cover_photo_smaller_size.png">
  <img width="100" height="100" src="https://res.cloudinary.com/practicaldev/image/fetch/s--YbV36HLj--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/hpg6if7btrwilqkidqbe.png">
  <img width="100" height="100" src="https://newrelic.com/sites/default/files/styles/og_image/public/2021-10/mongo_logo.jpg?h=2a479378&itok=_jsp1xWA">
  <img width="100" height="100" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLy-1SN4fo9U4Sn7S4aI_PyQr5x9sODPQ6V2-YHT4&s">
  <img width-"100" height="100" src="https://logowik.com/content/uploads/images/postman-api-platform6643.logowik.com.webp">
 
 ---
 # Use Of Library 📙: 
 
    🟠 body-parser
    🟠 connect-mongo
    🟠 data-parser
    🟠 dotenv
    🟠 express
    🟠 mongoose
    🟠 node-sass

---
