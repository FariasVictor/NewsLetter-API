# Newsletter RESTful Node API #

---

### What does this API uses? ###

##### * Node 10.15.2 
##### * MongoDB 4.2.3

---

### What is this API made for? ###

##### This API was made to be used with my other project, the *Newsletter Register*, this was my first ever RESFTful API. Basically both project was developed for study and learning reasons (_so maybe i haven't used the best pratices for it or even the best way to do the things. So don't goes mad with this_). At last if you think that have something i shold change, please, open a pull request. I would love to learn more with you :) .


---

### How can i run this? ###

##### First of all you need to install Node and MongoDB, so you can take a look on the [Node](https://linuxize.com/post/how-to-install-node-js-on-ubuntu-18.04/) and [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/) tutorials.

##### After that you need to run `sudo mkdir -p /data/db`
##### Run `npm install --save-dev nodemon`, `npm install express --save` 
##### And `npm install mongoose --save`
##### Then goes to the folder you cloned this repo and run `sudo mongod`*(Don't forget to use **sudo**)*
##### Finally run `sudo npm run start`

---

### How do i test if the API it's working? ###

##### I recommend use [Postman](https://linuxize.com/post/how-to-install-postman-on-ubuntu-18-04/) to do this.
##### It's very simple to use:

##### To test GET method:
###### Put the URL `http://localhost:3000/users` (depending on your host mapping you'll have to use `127.0.0.1:3000/users`) and click on "SEND". You'll receive the response `[]`

##### To test POST method:
###### Select POST, click on "Body" and "www-form-urlencoded". On the first key field enter "name", on the key field bellow you'll enter "email". on the first value field you can enter a name or whatever word you want, and on the email value you can do the same. Finally click on "SEND". You may see something like that: 




    [
        {
            "_id": "5e44128df5577428f9d47934",
            "name": "test",
            "email": "test@email.com",
            "__v": 0
        }
    ]


---

###### ...and that's it <3;

        