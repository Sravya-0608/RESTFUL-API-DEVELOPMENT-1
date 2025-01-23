# RESTFUL-API-DEVELOPMENT-1
** COMPANY**: CODTECH IT SOULTION
**NAME**: KURUPATI SRI SRAVYA
** INTERN ID**: CT08LTF
** DOMAIN** : SOFTWARE DEVELOPMENT
** BATCH DURATION**:JANUARY 15TH TO FEBRUARY 15TH
** MENTOR**: NEELA SANTHOSH
# ENTER DESCRIPTION OF TASK PERFORMED NOT LESS THAN 500 WORDS
** TASK 1**:RESTFUL API DEVELOPMENT USING NODEJS, EXPRESSJS
1.INSTALL OF NODE.JS
DOWNLOAD THE WINDOWS INSTALLER FROM THE NODE.JS WEBSITE.
CHOOSE THE LONG-TERM SUPPORT VERSION THAT'S SHOWN ON THE LEFT.
AFTER DOWNLOADING, INSTALL/RUM THE INSTALLER, AND THEN FOLLOW THE PROMPTS
1. node -v
DOWNLOAD AND INSTALL POSTMAN FOR EXPRESS
2. SET UP YOUR DEVELOPMENT ENVIRONMENT
. CREATE A FOLDER ON YOUR COMPUTER AND OPEN ON VISUAL STUDIO CODE
. CREATE A FILE AND NAME IT AS INDEX.JS
. INITIALIZE NPM USING (NPM INIT -Y) COMMAND IN TEMINAL
.INSTALL EXPRESS IN TEMINAL( npm install express) COMMAND
3. SETUP A SERVER FOR CURD RESTFUL API WITH NODE.JS AND EXPRESS
    .WRITE A SERVER APPLICATION CODE INSIDE THE INDEX.JS FILE
   . STAT THE SERVER (NODE INDEX.JS) TYPE THE COMMAND IN TEMINAL
   . INSTALL NODEMON (NPM INSTALL NODEMON) THEN ITS CREATE PACKAGE.JSON FILE ADD THIS COMMAND ON .JSON FILE("start":"nodemon index.js)
   . THEN START SERVER BY RUNNING THIS COMMAND (npm start)
4. CREATE API ROUTES
5. CREATE CRUD API
   1. GET/USERS - FIND ALL USERS
   2. POST/USERS - CREATES A USER
   3. GET/USERS/:ID - FIND A SPECIFIC USER
   4. DELETE/USERS/:ID - DELETES A SPECIFIC USER
   5. PATCH/USERS/:ID -UPDATES A SPEIFIC USER
6. GET/USERS END POINT
   . CREATE A NEW FOLDER CALLED ROUTES
   .CREATE A NEWFILE CALLED USERS.JS INSIDE THE ROUTES FOLDER.
   .WRITE THE CODE TO SET UP THE GET ROUTER
   . TEST API GET USING BROWSER COPY APIURL, AND PASTE IN CHROME / AND USE POSTMAN COPE SAME LINK USEING POST
7. POST/USER ENDPOINT
   . INSTALL UUID USING THIS COMMAND( npm install uuid)
   . USE USERS.JS FILE ONLY
   . WRITE THE CODE TO SET UP THE POST ROUTER
   . TEST API POST USING BROWSER COPY APIURL, AND PASTE IN CHROME / AND USE POSTMAN COPE SAME LINK USEING POST
8. GET/USERS/:ID ENDPOINT
   .USE USERS.JS FILE ONLY
   . WRITE THE CODE TO SET UP THE GET ROUTER
   . TEST API GET USING BROWSER COPY APIURL, AND PASTE IN CHROME / AND USE POSTMAN COPE SAME LINK USEING GET
   9. DELETE/USERS/:ID
       USE USERS.JS FILE ONLY
   . WRITE THE CODE TO SET UP THE DELETE ROUTER
   . TEST API DELETE USING BROWSER COPY APIURL, AND PASTE IN CHROME / AND USE POSTMAN COPE SAME LINK USEING DELETE
    10. PATCH/USERS/:ID ENDPOINT
        USE USERS.JS FILE ONLY
   . WRITE THE CODE TO SET UP THE PATCH ROUTER
   . TEST API PATCH USING BROWSER COPY APIURL, AND PASTE IN CHROME / AND USE POSTMAN COPE SAME LINK USEING PATCH
1. TESTING GET REQUEST IN POSTMAN
   . OPEN A NEW REQUEST TAB
   .SELECT "GET" FROM THE LIST AVAILABLE HTTP METHODS
   .IN THE URL FIELD, ENTER FULL URL WHERE YOU WANT TO SEND THE GET REQUEST.
   .FINALL, CILCK ON "SEND".
3.  TESTING POST REQUEST IN POSTMAN
   . OPEN A NEW REQUEST TAB
   .SELECT "POST" FROM THE LIST AVAILABLE HTTP METHODS
   .IN THE URL FIELD, ENTER FULL URL WHERE YOU WANT TO SEND THE POST REQUEST.
   . CLICK ON THE "BODY" TAB IN THE REQUEST WINDOW.
    . CHOOSE THE FORMAT IN WHICH YOU WANT TO SEND POST DATA.
    . ENTER THE DATE YOU WANT TO SEND IN THE REQUEST BODY.THIS DATE SHOULD MATCH THE FORMAT EXPECTED BY THE SERVER.
    . FINALL, CILCK ON "SEND".
3. TESTING GET REQUEST IN POSTMAN
   . OPEN A NEW REQUEST TAB
   .SELECT "GET" FROM THE LIST AVAILABLE HTTP METHODS
   .IN THE URL FIELD, ENTER FULL URL WHERE YOU WANT TO SEND THE GET REQUEST ADD ID
   .FINALL, CILCK ON "SEND".
4.  TESTING DELETE REQUEST IN POSTMAN
   . OPEN A NEW REQUEST TAB
   .SELECT "DELETE" FROM THE LIST AVAILABLE HTTP METHODS
   .IN THE URL FIELD, ENTER FULL URL WHERE YOU WANT TO SEND THE DELETE REQUEST ADD ID
   .FINALL, CILCK ON "SEND".
5.  TESTING PATCH REQUEST IN POSTMAN
   . OPEN A NEW REQUEST TAB
   .SELECT "PATCH" FROM THE LIST AVAILABLE HTTP METHODS
   .IN THE URL FIELD, ENTER FULL URL WHERE YOU WANT TO SEND THE PATCH REQUEST.
   . CLICK ON THE "BODY" TAB IN THE REQUEST WINDOW.
    . CHOOSE THE FORMAT IN WHICH YOU WANT TO SEND PATCH DATA.
    . ENTER THE DATE YOU WANT TO SEND IN THE REQUEST BODY.THIS DATE SHOULD ONLY INCLUDE THE SPECIFIC CHANGES YOU WANT TO MAKE TO THE RESOURCES
    . FINALL, CILCK ON "SEND"
