## Deployment:

### Windows Prerequisites:

The following applications need to be installed before the project can be replicated:



1. Download  Visual Studio Community 2019 Installer and run it.

    Link: [ https://visualstudio.microsoft.com/downloads/ ](https://visualstudio.microsoft.com/downloads/)


    In the installer, select these options from the workload and choose your installation location. Then, click install.

<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")



    .NET desktop development


    ASP.NET and web development


    Mobile development with .NET

2. Make an Atlassian account through Accutech

    Link: [https://id.atlassian.com/](https://id.atlassian.com/)

3. Once you are granted access to the repo, open up bitbucket via the following link:

    Link: [https://bitbucket.org/accutechdev/bsu.finwellapps/src/master/](https://bitbucket.org/accutechdev/bsu.finwellapps/src/master/)

1. Press “Clone”, and then copy the url from the git command, but do not include ‘git clone’. Thus, one should be left with: [https://{USERNAME}@bitbucket.org/accutechdev/bsu.finwellapps.git](https://galexthomas@bitbucket.org/accutechdev/bsu.finwellapps.git)

        

<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")



Once in Visual Studio, press clone repository.

In repository location, paste the url you obtained from the bitbucket and modify the path if desired. Next, press clone.

Once cloned, your file structure should look like this:



<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")


Install NuGet on Visual Studio 

Navigate to the Nuget Packet Manager by right clicking on the dependencies file and clicking on Manage NuGet Packages.

Once there click on the Installed tab and ensure that you have all of the shown packages downloaded. If not, you can install missing packages by going back to the browse tab and searching for them.



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")


Install PostgreSQL version 13.1 using default options.

Link: [https://www.enterprisedb.com/downloads/postgres-postgresql-downloads](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)

Make a Postman account and install it using default options.

[https://www.postman.com/downloads/](https://www.postman.com/downloads/)

Install pgAdmin4 version 4.28 using default options.

[https://www.pgadmin.org/download/pgadmin-4-windows/](https://www.pgadmin.org/download/pgadmin-4-windows/)


### Building and compiling:

For PgAdmin4



1. Open pgAdmin4
2. Select “Add New Server”
3. Give it a name of FinwellDB
4. On the connection tab make the host “localhost”
5. Set the password to whatever you want. But that password must match in step 4 of Visual Studio.
6. Save the server created.

For Visual Studio



1. Open Visual Studio
2. Open FinwellAPI -> appsettings.json
3. On line 11 change the “password=____” to the password created on step 5 in PgAdmin4.

Once those 2 things have been completed the program should be functional on your computer


### Final Result

If everything has gone correctly, running the program in Visual Studio should open a page on swagger. It should appear like this



<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")




1. Select the Income “GET /Income” button
2. Change the media type to text/json on the drop down menu
3. Press the “Try it out” button
4. The return should look like

{

  "income": 0

}



5. Click “execute”
6. It should then return with a “request URL” section with a result similar to 

    https://localhost:44388/Income

7. Copy yours which likely has a different number after localhost
8. Leave this tab open as we will come back to it later

**Open Postman**



1. Select + New near the top left.
2. Select Request
3. Insert anything (We suggest “Test Request” for simplicity) for the request name
4. Insert it or create a collection to put it into. (that name also doesn't matter)
5. On the “Enter request URL” you should now paste the copied link from step 6 from the previous section.
6. Select “Body”
7. On the body page select the “raw” button
8. Change the “Text” to “JSON”
9. Go back to the swagger page and copy the following:

{

  "income": 0

}

Section and paste it into the body Change the 0 into a larger number such as 200.



10. Now click “Send”. The result should look like this: 

    

<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.png "image_tooltip")




### Troubleshooting

	Common errors include:



*    `ECONNREFUSED<sub>, </sub>`which occurs when the request cannot be sent from Postman
    *   Go back to Visual Studio, and then make sure the program is running by checking whether the button has switched to a “Stop Sign”, which indicates that “Play” has already been pushed.

        

<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")



        

<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image8.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image8.png "image_tooltip")


    *   In pgAdmin, Make sure the database is connected by right-clicking on the database in the navigation section on the left hand side of the screen, and then clicking “connect”.
*   Connection string error, which occurs when your password is invalid.
    *   Navigate back to FinwellAPI -> appsettings.json and making sure the password in line 11 is the password you created in pgAdmin.
