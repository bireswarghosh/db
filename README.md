﻿# HOW TO work MONGO-DB  
           

## some prerequire step like -->>

1. downlode MONGODB through the official website
2. and install it ; when i install, automaticly add compass with it and go on....
   it take some tyme
 
## HOW TO use MONGO-DB

** BUT untill this point i all rady creat contract list **

i add mongo through the step

### Connecting to MongoDB using mongoose.js

# STEP - 1 .

open my terminal and write this line(npm install mongoose).

# s-2

{

    <!-- this step does by coding ninga  -->

first of all i creat a folde(config) & under the folder i creat a file (mongoose.js)
where i setup my mongo [reference through {https://mongoosejs.com/docs/5.x/docs/index.html} there
are avalable both of varson 5 & 7 ( but i am refer through v.5)]
doing this all work
add a line index.js that is ( const db = require('./config/mongoose'); )
}

{
another approch is -->
do all mongose setup in index.js(i comment-out this section)

}

### Creating the DB Schema



# step -1 .
to creat a folder moduels & with it creat a file contact


#### Populating the DB
 
  ## step -1 .
   i go to the app.post secetion and add     Contact.create where i add new new name and phone    name: req.body.name,
        phone: req.body.phone and creat a new function where i saya that if err  show err or otherwise creat a new .




 ### Fetching Data from DB


# step-1.
hear i go to app.get method wher i fatching  . 



### Deleting From DB
 ## step -1.
  hear i search contract by id , beacuse there are present more than one person who hava  same name or same phone  ; for this resone i go to search by id . for serching id we goes to home.ejs file  and change the  ; delate button search by id .
  or id that is creat by mongose through automataicly.




               ##### thank you foe reading it #### 
