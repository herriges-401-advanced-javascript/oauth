# oauth
comparative analysis
wordpress:
research conducted by Lulu , kateryna, Matt, and Joshua.
overall score: 2/10. 
Pros: 
1. There weren't so many docs that you got lost as a developer. 
2. It was easy to create an application. 
Cons:
1. You need a wordpress website to make it work.
2. It would have been better to have instructions for different scenarios/languages.
3. What if's were mentioned but not expanded on.

Documentation:
https://developer.wordpress.com/docs/oauth2/

The documentation was easy to read but lacking in some regards. The docs specifically mentioned "if all goes well you will receive stuff" but didn't point out what to do if things didn't go well. 

System Requirements:
Dependencies:
    "base-64": "^0.1.0",
    "bcrypt": "^5.0.0",
    "dotenv": "^8.2.0",
    "express": "^4.17.1",
    "jsonwebtoken": "^8.5.1",
    "superagent": "^6.0.0"

Ramp Up Projections:
It would take an indefinite ammount of time for this to be ramped up because we haven't been able to get it to take the first step. It may never walk. 

Community Support:
Niche framework with only some communities using it for oauth. 

Operating Instructions:
1. Create a dotenv (.env) with:
CLIENT_SECRET=< your client secret >
CLIENT_ID= < your client id >
JWT_SECRET= < your secret phrase >
2. run "npm i" to install dependencies
3. run "nodemon" or "node ." to start the server
4. go to "http://localhost/3000" in your browser.
