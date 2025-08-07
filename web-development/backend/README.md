# ⚙️ Backend Development Resources

Backend development focuses on server-side programming, databases, APIs, and the infrastructure that powers web applications.

## 📋 Table of Contents

- [Server-Side Programming](#server-side-programming)
- [Databases](#databases)
- [ORMs (Object-Relational Mapping)](#orms-object-relational-mapping)
- [APIs](#apis)
- [Caching](#caching)
- [Web Security](#web-security)
- [Testing](#testing)
- [CI/CD](#cicd)

## 💻 Server-Side Programming

### Node.js
A JavaScript runtime built on Chrome's V8 JavaScript engine for building server-side applications.

#### Documentation
- [Node.js Official Docs](http://nodejs.org/docs/latest/api/) - Official Node.js API documentation
- [Express.js](https://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js
- [Node.js Best Practices](https://github.com/goldbergyoni/nodebestpractices) - Summary of best practices for Node.js
- [Google Cloud Node.js Docs](https://cloud.google.com/nodejs/docs) - Node.js on Google Cloud Platform
- [MDN Node.js Guide](https://developer.mozilla.org/en-US/docs/Glossary/Node.js) - Node.js fundamentals on MDN

#### Video Tutorials - English
- [Node.js Tutorial Series - The Net Ninja](https://www.youtube.com/watch?v=5eaBOxXABkU&list=PL1BztTYDF-QPdTvgsjf8HOwO4ZVl_LhxS) - Comprehensive Node.js course
- [Node.js and Express.js Full Course - Codevolution](https://www.youtube.com/watch?v=LAUi8pPlcUM&list=PLC3y8-rFHvwh8shCMHFA5kWxD9PaPwxaY) - Complete Node.js and Express.js tutorial
- [Node.js Tutorial - Navin Reddy](https://www.youtube.com/watch?v=yEHCfRWz-EI&list=PLsyeobzWxl7occsESx2X1E2R2Uw5wCoeG) - Node.js from basics to advanced

#### Video Tutorials - Hindi
- [Node.js Tutorial in Hindi - Thapa Technical](https://www.youtube.com/watch?v=ohIAiuHMKMI&list=PLinedj3B30sDby4Al-i13hQJGQoRQDfPo) - Complete Node.js tutorial in Hindi
- [Node.js Course - Technical Thapa](https://www.youtube.com/watch?v=AZzV3wZCvI4&list=PL78RhpUUKSwfeSOOwfE9x6l5jTjn5LbY3) - In-depth Node.js course in Hindi
- [Node.js in One Video - CodeWithHarry](https://www.youtube.com/watch?v=BLl32FvcdVM) - Quick Node.js overview in Hindi

### Python
Python is excellent for backend development with frameworks like Django and Flask.

#### Frameworks
- [Django Documentation](https://docs.djangoproject.com/) - Official Django documentation
- [Flask](https://flask.palletsprojects.com/) - Lightweight web framework for Python
- [FastAPI](https://fastapi.tiangolo.com/) - Modern, fast web framework for building APIs with Python

#### Video Tutorials - English
- [Django Tutorial for Beginners - Programming with Mosh](https://www.youtube.com/watch?v=UmljXZIypDc) - From project setup to deployment
- [Django Crash Course - Traversy Media](https://www.youtube.com/watch?v=F5mRW0jo-U4) - Quick-start guide covering models, views, templates
- [Build REST APIs with Django - John Elder](https://www.youtube.com/watch?v=6c36HBymutc) - Focused on Django REST Framework

#### Video Tutorials - Hindi
- [Django Tutorial in Hindi - CodeWithHarry](https://www.youtube.com/watch?v=_nuuyTNG3O4) - End-to-end Django project
- [Django Course - Thapa Technical](https://www.youtube.com/watch?v=_TLhUCjY9iA) - Detailed explanations of core concepts

## 🗄️ Databases

A database is an organized collection of data, generally stored and accessed electronically from a computer system.

### PostgreSQL
A powerful, open-source object-relational database system with over 30 years of active development.

#### Documentation
- [PostgreSQL Official Docs](https://www.postgresql.org/docs/) - The official PostgreSQL documentation
- [PostgreSQL Tutorial](https://www.postgresqltutorial.com/) - A comprehensive collection of tutorials and guides

#### Video Tutorials - English
- [Learn PostgreSQL Tutorial - Full Course for Beginners](http://www.youtube.com/watch?v=qw--VYLpxG4) - A comprehensive course from freeCodeCamp
- [PostgreSQL in 100 Seconds](http://www.youtube.com/watch?v=n2Fluyr3lbc) - A quick overview by Fireship

#### Video Tutorials - Hindi
- [Master POSTGRESQL in ONE VIDEO](http://www.youtube.com/watch?v=cnzka7kF5Zk) - A beginner to advanced course by MPrashant TECH
- [Effortless postgreSQL installation instructions](http://www.youtube.com/watch?v=EhapnaEKl-w) - A guide by Chai aur Code

### MongoDB
A source-available cross-platform document-oriented database program. Classified as a NoSQL database program.

#### Documentation
- [MongoDB Official Docs](https://docs.mongodb.com/) - The official MongoDB documentation
- [MongoDB University](https://university.mongodb.com/) - Free online courses from MongoDB

#### Video Tutorials - English
- [MongoDB in 100 Seconds](http://www.youtube.com/watch?v=-bt_y4Loofg) - A quick overview by Fireship
- [Learn MongoDB in 1 Hour](http://www.youtube.com/watch?v=c2M-rlkkT5o) - A tutorial by Bro Code

#### Video Tutorials - Hindi
- [MongoDb Tutorial For Beginners in Hindi](http://www.youtube.com/watch?v=oSIv-E60NiU) - A tutorial by CodeWithHarry
- [MongoDB Complete Course Tutorial in Hindi](http://www.youtube.com/watch?v=rU9ZODw5yvU) - A complete course from Thapa Technical

### Redis
An in-memory data structure store, used as a distributed, in-memory key–value database, cache and message broker.

#### Documentation
- [Redis Official Docs](https://redis.io/documentation) - The official Redis documentation
- [Redis University](https://redis.com/redis-enterprise/training/redis-university/) - Free online courses from Redis

#### Video Tutorials - English
- [Redis in 100 Seconds](http://www.youtube.com/watch?v=G1rOthIU-uo) - A quick overview by Fireship
- [Redis Crash Course](http://www.youtube.com/watch?v=jgpVdJB2sKQ) - A crash course from Web Dev Simplified

#### Video Tutorials - Hindi
- [Redis: This can change your Database Game - Here how!](http://www.youtube.com/watch?v=rsHq4NPDEs0) - A video by CodeWithHarry
- [Redis Crash Course](http://www.youtube.com/watch?v=Vx2zPMPvmug) - A crash course by Piyush Garg

## 🔄 ORMs (Object-Relational Mapping)

Object-Relational Mapping (ORM) is a technique that lets you query and manipulate data from a database using an object-oriented paradigm.

### Prisma
A next-generation Node.js and TypeScript ORM with type-safety and auto-completion.

#### Documentation
- [Prisma Official Docs](https://www.prisma.io/docs/) - The official Prisma documentation
- [Prisma Examples](https://github.com/prisma/prisma-examples) - A collection of examples using Prisma

#### Video Tutorials - English
- [Prisma in 100 Seconds](http://www.youtube.com/watch?v=rLRIB6AF2Dg) - A quick overview by Fireship
- [Learn Prisma In 60 Minutes](http://www.youtube.com/watch?v=RebA5J-rlwg) - A tutorial by Web Dev Simplified

#### Video Tutorials - Hindi
- [Prisma ORM in One Video](http://www.youtube.com/watch?v=-_nz4q_Cyr4) - A video by Thapa Technical
- [Crash Course on Prisma ORM with Express JS, Postgres and Build a REST API's](http://www.youtube.com/watch?v=GReoWKUnwAg) - A crash course from Coding with Tushar

### Mongoose
A MongoDB object modeling tool designed to work in an asynchronous environment.

#### Documentation
- [Mongoose Official Docs](https://mongoosejs.com/docs/) - The official Mongoose documentation

#### Video Tutorials - English
- [Mongoose Crash Course - Beginner Through Advanced](http://www.youtube.com/watch?v=DZBGEVgL2eE) - A crash course by Web Dev Simplified
- [Intro to MongoDB and Mongoose](http://www.youtube.com/watch?v=-PdjUx9JZ2E) - A tutorial by Dave Gray

#### Video Tutorials - Hindi
- [MongoDB, Mongoose & Database Management](http://www.youtube.com/watch?v=4TFA-vy_fdo) - A video by Sheryians Coding School
- [Data modelling for backend with mongoose](http://www.youtube.com/watch?v=VbGl3msgce8) - A tutorial by Chai aur Code

### SQLAlchemy
The Python SQL toolkit and Object Relational Mapper.

#### Documentation
- [SQLAlchemy Official Docs](https://www.sqlalchemy.org/docs/) - The official SQLAlchemy documentation

#### Video Tutorials - English
- [SQLAlchemy: The BEST SQL Database Library in Python](http://www.youtube.com/watch?v=aAy-B6KPld8) - A video by ArjanCodes
- [SQLAlchemy Turns Python Objects Into Database Entries](http://www.youtube.com/watch?v=AKQ3XEDI9Mw) - A video by NeuralNine

#### Video Tutorials - Hindi
- [Flask SQLAlchemy Tutorial In Hindi](http://www.youtube.com/watch?v=9CQp7aoc1IU) - A tutorial by CodeWithHarry
- [SQLAlchemy ORM Crash Course 2025](http://www.youtube.com/watch?v=XBMHmIc5lv0) - A crash course by Geeky Shows

## 🔌 APIs

An Application Programming Interface (API) is a way for two or more computer programs to communicate with each other.

### REST
Representational State Transfer (REST) is a software architectural style for creating Web services.

#### Documentation
- [REST API Tutorial](https://restfulapi.net/) - An informational website about REST APIs
- [Introduction to REST](https://www.codecademy.com/articles/what-is-rest) - An article by Codecademy

#### Video Tutorials - English
- [What Is REST API? Examples And How To Use It](http://www.youtube.com/watch?v=-mN3VyJuCjM) - A video by ByteByteGo
- [REST API Crash Course](http://www.youtube.com/watch?v=qbLc5a9jdXo) - A crash course by Caleb Curry

#### Video Tutorials - Hindi
- [What is REST API?](http://www.youtube.com/watch?v=o7ePQ_M_jsc) - A video by Great Learning
- [What is an API? Simply Explained](http://www.youtube.com/watch?v=XGa4onZP66Q) - A video by Apna College

### GraphQL
A query language for APIs that gives clients the power to ask for exactly what they need.

#### Documentation
- [GraphQL Official Docs](https://graphql.org/learn/) - The official GraphQL documentation
- [How to GraphQL](https://www.howtographql.com/) - A free and open-source tutorial to learn GraphQL

#### Video Tutorials - English
- [GraphQL Explained in 100 Seconds](http://www.youtube.com/watch?v=eIQh02xuVw4) - A quick overview by Fireship
- [GraphQL Course for Beginners](http://www.youtube.com/watch?v=5199E50O7SI) - A course by freeCodeCamp.org

#### Video Tutorials - Hindi
- [GraphQL Crash Course - GraphQL NodeJS](http://www.youtube.com/watch?v=WtkKwO1viI8) - A crash course by Piyush Garg
- [Why GraphQL | GraphQL vs REST API](http://www.youtube.com/watch?v=NNNcoWZ6Ih0) - A video by CODERS NEVER QUIT

## ⚡ Caching

A high-speed data storage layer which stores a subset of data for faster access than the primary storage location.

### Documentation
- [Caching Strategies and How to Choose the Right One](https://codeahoy.com/2017/08/11/caching-strategies-and-how-to-choose-the-right-one/) - An article on caching strategies
- [Introduction to Caching](https://aws.amazon.com/caching/) - An introduction by AWS

### Video Tutorials - English
- [Redis Crash Course - the What, Why and How to use Redis as your primary database](http://www.youtube.com/watch?v=OqCK95AS-YE) - A crash course by TechWorld with Nana

### Video Tutorials - Hindi
- [Redis Caching: 5x Faster API Performance | Crash Course](http://www.youtube.com/watch?v=_yUGiQa6H54) - A crash course by Coder's Gyan
- [What is Redis?](http://www.youtube.com/watch?v=m_RIEG8gyoA) - A video by Build with Akshit

## 🔒 Web Security

Web security refers to the protective measures and protocols that protect websites, web applications, and web services from security threats.

### Documentation
- [OWASP Top Ten](https://owasp.org/www-project-top-ten/) - The Open Web Application Security Project's list of the 10 most critical web application security risks
- [MDN Web Security](https://developer.mozilla.org/en-US/docs/Web/Security) - Web security documentation by Mozilla

### Video Tutorials - English
- [Web Application Security Fundamentals](http://www.youtube.com/watch?v=-7OX58nHPb8) - A video by Embrace The Red
- [OWASP Top 10 2021 - The List and How You Should Use It](http://www.youtube.com/watch?v=hryt-rCLJUA) - A video by Cyber Citadel

### Video Tutorials - Hindi
- [What is Cyber Security With Full Information?](http://www.youtube.com/watch?v=VBejkJSsHZ0) - A video by Quick Support
- [OWASP Top 10 Vulnerabilities in Hindi](http://www.youtube.com/watch?v=HE244moNuXE) - A video by Cyberwings Security

## 🧪 Testing

Software testing is the process of evaluating and verifying that a software product does what it is supposed to do.

### Documentation
- [Software Testing Tutorial](https://www.guru99.com/software-testing-introduction-importance.html) - A tutorial on software testing
- [Jest](https://jestjs.io/) - A delightful JavaScript Testing Framework with a focus on simplicity
- [Pytest](https://docs.pytest.org/en/7.x/) - A framework that makes it easy to write small, readable tests

### Video Tutorials - English
- [5 Types of Testing Software Every Developer Needs to Know!](http://www.youtube.com/watch?v=YaXJeUkBe4Y) - A video by Alex Hyett
- [Software Testing Explained in 100 Seconds](http://www.youtube.com/watch?v=u6QfIXgjwGQ) - A video by Fireship

### Video Tutorials - Hindi
- [Software Testing Tutorial For Beginners In Hindi](https://www.youtube.com/watch?v=k_h82m6DA_M) - A tutorial by WsCube Tech
- [What is Software Testing? Full Course in 3 Hours](https://www.youtube.com/watch?v=x5sY2y222IM) - A course by Great Learning

## 🔄 CI/CD

CI and CD stand for continuous integration and continuous delivery/continuous deployment. It's a method to frequently deliver apps to customers through automation.

### Documentation
- [What is CI/CD?](https://about.gitlab.com/topics/ci-cd/) - An explanation from GitLab
- [GitHub Actions](https://github.com/features/actions) - Automate your workflow from idea to production

### Video Tutorials - English
- [DevOps CI/CD Explained in 100 Seconds](http://www.youtube.com/watch?v=scEDHsr3APg) - A quick overview by Fireship
- [GitHub Actions Tutorial - Basic Concepts and CI/CD Pipeline with Docker](http://www.youtube.com/watch?v=R8_veQiYBjI) - A tutorial by TechWorld with Nana

### Video Tutorials - Hindi
- [What is CI/CD? | Complete DevOps CI/CD Pipeline explained](https://www.youtube.com/watch?v=F_Y05sC2s_k) - A video by edureka! Hindi
- [CI/CD Pipeline with Jenkins and GitHub | Jenkins Tutorial in Hindi](https://www.youtube.com/watch?v=wEV857aP3dc) - A tutorial by Automation Hindi

---

**Next Steps**: Ready to combine frontend and backend? Check out [Fullstack Development](../fullstack/README.md) to learn how to build complete web applications!
