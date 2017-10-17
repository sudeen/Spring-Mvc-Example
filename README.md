# Spring-Mvc-Example
##Spring Mvc Template for Hello World. 

Right Click on main directory and create a directory named webapp.
Under the `webapp` create another directory named **_WEB-INF_**.

Right click on your Project folder name and click on add framework support 
and then tick the web and then ok button. 
After this you will get a folder named web which contains the `web.xml` file. Copy
the web.xml file and paste it under your **_WEB-INF_** directory 
and delete the generate web folder.

After this go to your project structure (can be found in the file tab) 
and go to **_facets_** and choose web.

Under the _**Deployment Descriptors**_ change the **path** to the newly created `web.xml`.

Under the _**Web Resource Directories**_ edit the Web Resource Directory path to 
point the **_WEB-INF_** directory.

To add the `dispatcher-servlet.xml` file again right click the project folder and 
click on add framework support and then find spring under that spring tick the 
**_spring mvc_**, then the dispatcher-servlet file 
will be automatically added/generated.

`But ` for some reasons I could not find this spring mvc tick mark option.
So, I copied this `dispatcher-servlet.xml` file from another source.

Lastly, all you need to do is setup a **_Tomcat Server_**.
While configuring tomcat server you will see the fix icon 
just click on that icon and intellij will automatically help you to make the `WAR` file.

You must face an error in the first run so to fix this go to the project structure
and under the **_artifacts_** tab you will see the name **_Available Elements_**
and under that tab you will see some files probably 4 or 5 files. Select all those
right click and click add to lib. 
Restart the server and you will get the desired output.
   
