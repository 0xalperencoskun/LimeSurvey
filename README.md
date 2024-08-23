# LimeSurvey
LimeSurvey XSS

Summary:
Survey name filtering is not applied during survey creation phase. Survey names may contain malicious js codes.<br>

Steps:
1- Login LimeSurvey app.<br>
2- Click the create survey button.<br>
3- Set BurpSuite Intercept On<br>
4- Write survey name and click create survey button.<br>
5- I added <script>alert(8)</script> to the end of the name.<br>
6- Open the survey and xss vulnerability is here.<br>



https://github.com/user-attachments/assets/4c93b265-8f26-4529-88d6-4a6f6ed7da28

