# LAB - Class 7

## Project: Bearer-Auth

### Author: Odushina, Timothee

### Problem Domain

Create a UML diagram of the authentication system on a whiteboard before you start

1. Refer to the Getting Started guide in the lab submission instructions
2. Create a new repository called bearer-auth
3. Copy the files from within the starter-code folder of your class repository into your new repo as a starting point
4. Work in a new branch called dev, created from main
5. Following completion of this assignment, create a Pull Request from dev to main and merge your code
    * You will deploy from your main branch to a new app at Heroku
    * You will add a link to the PR that you merged in your README for grading purposes

### Links and Resources

- [GitHub Link](https://github.com/timothee2022/bearer-auth)

#### `.env` requirements

PORT=3001
DATABASE_URL=postgres://localhost:5432/api-app?sslmode=disable

#### How to initialize/run your application

* `npm start`
* `nodemon`

#### Features / Routes

* GET : `/hello`
* GET : `/secret`
* PUT : `/signup`
* PUT : `/signin`

#### Tests

* I have set up testing for each files to make sure they are all working as expected.
* Run the `npm test {name of the file you are testing}`

