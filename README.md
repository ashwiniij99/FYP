# FYP
Final Year Project-Cyberbullying detection in social media text
In the project implemented the detection of cyberbully words on twitter are integrated into one application, alongside these the cyberbully contents within the tweet comments are going to be detected using Linear SVM algorithm. The project consists of a web-based application build in Django that includes a dashboard for users to monitor cyberbullying texts in social media.

Proposed System : 

![image](https://user-images.githubusercontent.com/55174251/129469526-d76394bb-3f32-45e1-80f3-cb9486906f20.png)

OUTPUT SCREENSHOTS :

1. LOGIN PAGE : Username and Email is stored in the database as soon as user login to this page. After logging in we can see a dashboard giving complete analysis of the twitter account as shown in the below screenshot.

![image](https://user-images.githubusercontent.com/55174251/129469540-56b4a343-82a8-49bf-a8aa-f2fc1037c587.png)

DASHBOARD : This is dashboard that comes up as soon as user is logged in. 

Features of the dashboard: 
1. Username is displayed on the left corner of the navbar of user currently logged in. 
2. 2. Cards display: 
   i. Number of tweets done by user 
   ii. Number of Replies on user’s tweets 
   iii. Number of Non-Cyberbully texts predicted by ML model. 
   iv. Number of Cyberbully texts predicted by ML model 
3. Pie chart that displays the percentage of Bully texts predicted to the Non-bully texts predicted. 
4. Table that displays complete detail of tweets and replies, along with the predictions made by the ML model. 
5. Logout button provided on right side of the navbar that takes back to the login page for new session.
6. 
![Dashboard](https://user-images.githubusercontent.com/55174251/129469548-2e61940a-cf3e-465d-9036-79ccac08a930.JPG)

WARNING EMAIL SENT TO THE USER :

![Gmail ss 2](https://user-images.githubusercontent.com/55174251/129469604-98010d66-7200-43ae-ac5b-551c2297a540.JPG)

Conclusion : 
The proposed work is focused on detecting the occurrence of cyberbullying in twitter networks using machine learning algorithm Linear SVM and TfidfVectorizer. This system will definitely help in tracing cyberbully texts on particular users twitter account.
