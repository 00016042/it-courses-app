!!!This web application was created to fulfill Web Technology module’s requirements and does not represent an actual company or service


About the app: this app is developed for the imaginary IT based educational center. this app consists of four models which are: category.js, customer.js, course.js, and enrollment.js. By using this modules, data about the category of the course, about the customers which are the students going to study in any of this educational center's course, about the courses available in this facility and about the enrollments could be stored to the database. I have used get method to get the informations about all info in one model. For instance if i want to get all courses in database i se get method. It was used put, post, delete, methods to update, create a new, and delete the informations on the database.

How to run the app locally: to run this up, user should type nodemon index.js. Because i have installed nodemon package to this project so that it could run it automatically after making any changings on the coding part. If you do not want to do so you can easily run it by writing npm start to the terminal. If it works properly without any mistakes it will be shown the result on the terminal and you will see the text "5000chi portni eshitishni boshladim...", "[nodemon] starting `node index.js`", and if you install the mongo db or if you already have you shuld give this order on terminal or other alternatives can be used, to start mongodb "sudo service mongod start" and write "mongo" to the terminal again and it will start working and if sucsessfully connect to the mongodb you will see the text "MongoDBga ulanish hosil qilindi..." on the terminal. Moreover i have used mongoose package on my project therefore you also need to install mongoose package to run from this app properly. !!Remenber that the mongoose could not work or connect to the mongodb if you install a new version of mongose than 5 .therefore install untill 5 version if you install the same version of mongoose it will not be any problem with it. Moreover to use from the pug functions you should install pug package as well to your visual studio code.
And this project is named with 5000 and if want to run it on browser just write http//localhost:5000 and if you want to see other models you should put /api/and the name of the model. for example you should put http://localhost:5000/api/courses by running this you could see the courses on the datebase on browser. Moreover i suggest you to use from the postman app to check the back end part of my code, this because i have not finished the some front end parts not fully. I myself used postman to test my back end codes. you could install it from postman.com website on the internet. And i have installed mongodb compass from website of it if you want you could download it and se the datas on the database.
Moreover, i have used from the joi package for the validation purposes. you should also need to install it on your code reader or editor. Furthermore you should install express for run this project correctly.

application dependencies’ list: they are  written with their versions as well. 
    "express": "^4.18.3",
    "joi": "^17.12.2",
    "mongoose": "^5.13.0",
    "nodemon": "^3.1.0",
    "pug": "^3.0.2"

Link for the git hub: https://github.com/00016042/my-testing-repo.git

Link for the website of my deployed app: 


