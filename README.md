# deployed app



# Tech-Blog
This is a basic CMS-style blog site that was created using the Model, View, Controller paradigm. This application was created using Node.js, express for the server, and sequelize to connect to a mysql database entitled "tech_blog_db". All user, post, and comment data is stored in tech_blog_db. All passwords have been encrypted using the bcrypt Node.js package. The HTML views templates are generated using Handlebars.js.

# Installation
1. You will need to head to (https://github.com/Stew5555/mvcTechBlog), and install the code! 

2. After that navigate through the terminal to install some npm packages for this project to work. And these packages are ["bcrypt": "^5.0.1", "connect-session-sequelize": "^7.1.5", "dotenv": "^16.0.3", "express": "^4.18.2", "express-handlebars": "^6.0.6", "express-session": "^1.17.3", "mysql2": "^2.3.3", "sequelize": "^6.23.1", "sqlite3": "^5.1.1"]. 

3. Once you've installed these packages, log in through mysql in the terminal, and source the schema file! after that you can quit from mysql

4. After that you can quit from mysql, and run the seed folder by typing npm run seed.

5. And finally type in node server.js on the terminal, and your all set! copy the local host link and paste it on your favorite browser.