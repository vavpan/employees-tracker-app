   <b>EMPLOYEES-TRACKER-APP</b>


<b> About the App <b>
<p> An App which allows us to track employees. There are 3 types of users who can login (Employee,Manager,Admin) and according to your role you can view/search or manage the employees such as add,update and delete them. Using Spring Security the user's password is encrypted in database. </p>

![empl-tracker](https://user-images.githubusercontent.com/74924160/191194814-3c56f3ae-72e6-4d4b-aa10-76ef5170fa17.png)


![pass-encrypt](https://user-images.githubusercontent.com/74924160/191194903-c1bf4761-455a-4936-81a7-74b804e35367.png)
<br><br><br><br>
<b> Technologies used: </b>
<ul>
<li>Java</li>
<li>Spring MVC</li>
<li>Spring Security</li>
<li>Hibernate</li>
<li>Maven</li>
<li>Thymeleaf</li>
<li>Html</li>
<li>CSS</li>
</ul>


 ==== Software And Tools Required ====
 <ul>
<li>MySQL Workbench</li>
<li>Eclipse/Intellij</li>
</ul>

<b>Execution:</b>

First, you need to run the two sql scripts which are included in the source code and run them into MySQL Workbench in order to create the databases for users and employees. Afterward your need to add your <u>username</u> and your <u>password</u> in the <u>application.properties</u> file on <u>src/main/resources</ul>. The lines that must be modified are as follows:

app.datasource.username=
<br>
app.datasource.password=

Once it's done you can run the app:
*Double click on <u>ThymeleafdemoApplication</u>
*Once you are inside the class, right click -> Run As -> Java Application

User: John ---> Password: test <br>
User: Mike ---> Password: test <br>
User Mary  ---> Password: test

