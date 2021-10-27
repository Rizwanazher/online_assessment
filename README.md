# Final_Project:
This is an online assessment platform made by Rizwan Azher Saudager and Samina Abbas as the final project of Walkover University training program. The technologies that have been used to create the web application are HTML, CSS, JavaScript and Bootstrap and for deployment we uses aws cloud and jenkins as a CI/CD tool.
And this is the public IP address of our deployed project- 13.211.207.189 and link for the same- http://13.211.207.189
And we also host our project in git hub and this is the link- https://rizwanazher.github.io/online_assessment/
# Developers:
  1. Samina Abbas 
    GitHub profile - https://github.com/saminaabbas

  2. Rizwan azher saudager
    GitHub profile - https://github.com/Rizwanazher

# Specifications:
1. The assessment is MCQ based.

2. There is a pool of questions for the assessment.

3. The Questions displayed in the assessment shall only be from that pool.
 
4. The test will be conducted for a time of 80 seconds and a timer has been set to ensure the same.

5. The score for the assessment will be generated at the end of the assessment.


# Tech Stack:
1. HTML
2. CSS
3. Javascript
4. Bootstrap

# Deployment:
 ---we deployed our website using amazon aws using its EC2 services---
 1. we initially create the Instance using EC2 in redhat .
 2. then we installed httpd server into red-hat instance which is operated using putty.
 3. then we attach our github repo into httpd directory using jenkins.
 4. finally we host our website into the httpd server. 

# CI/CD setup:-
--we used jinkins as our CI/CD tool--
1.we Created a GitHub repository of our project.

2.we Install git via terminal.

3. Then we clone that repository into our local pc and then added our project files in it . 

4. Added all the changes we want.and commited them as well as push them into the github repo.

6. then we installed jenkins and git into our red-hat instance.

7.into the jenkins we setup the  githug plugin throgh which we connect our project repository 
  jenkins which created image of gitub file into it and we also configur the buid now button such 
  that it auto fetch our github repo data in every 3 minutes.

8. then we configur jinkins setting so that it can give its github rep fetched  data to out httpd
  server so that we could ultimetly host our website. for this to happen we have to give authentication
  setting to jinkins for allowing its access to httpd directory.


