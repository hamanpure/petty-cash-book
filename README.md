## petty-cash-book

this is a project made during a 12 hour hackathon conducted at my uni. the problem statement summarized is as follows; to make a web app that can serve as a personalized app where a user can record and analyze their financial transactions

note that the application was built in a time crunch and the frontend is not responsive; it should although work on laptop screens and larger

All of the dependencies and tools I have used are as follows

- Node.JS / Express.JS
    - body-parser
    - dotenv
    - ejs
    - express
    - mongoose
    - mongodb
- EJS (Embedded Javascript)
- MongoDB / Mongoose (ODM)

the application is divided into three segments i.e
1. A landing for user to navigate through
2. A ledger page to insert transaction details into a database
3. An analytics page

![image](https://github.com/gnaaruag/petty-cash-book/assets/68043860/53f5140f-65a6-4286-ad38-6d6118ea4571)
![image](https://github.com/gnaaruag/petty-cash-book/assets/68043860/3f1a4d5f-d028-4a06-9d3e-9795a8ef13b0)
![image](https://github.com/gnaaruag/petty-cash-book/assets/68043860/a686ed0f-c0dd-42fa-b9bf-3e4d0223d20a)

deployed on [Render](https://petty-cash-app.onrender.com)
the deployment has a couple minor errors due to server date formats, but everything else works fine
