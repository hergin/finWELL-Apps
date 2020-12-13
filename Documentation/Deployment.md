
## Deployment:

### Windows Prerequisites:

The following applications need to be installed before the project can be replicated:

  

1.  Download Visual Studio Community 2019 Installer and run it.
    

Link: [https://visualstudio.microsoft.com/downloads/](https://visualstudio.microsoft.com/downloads/)

In the installer, select these options from the workload and choose your installation location. Then, click install.![](https://lh4.googleusercontent.com/ZPM2vF6I1bgf9n2c5S4LseFGYfvAKF-TGnlZ3tArJsoYR4gcbe7k-SXLPCX7h4G-ipf4_wvSU8AO01XCC9y0r6RsZ7q25snKL_VTnbKryZcRIZb6Rd_9LEHu-lLCgb0Yr13PUrY3)

.NET desktop development

ASP.NET and web development

Mobile development with .NET

2.  Make an Atlassian account through Accutech
    

Link: [https://id.atlassian.com/](https://id.atlassian.com/)

  

3.  Once you are granted access to the repo, open up bitbucket via the following link:
    

Link: [https://bitbucket.org/accutechdev/bsu.finwellapps/src/master/](https://bitbucket.org/accutechdev/bsu.finwellapps/src/master/)

1.  Press “Clone”, and then copy the url from the git command, but do not include ‘git clone’. Thus, one should be left with: [https://{USERNAME}@bitbucket.org/accutechdev/bsu.finwellapps.git](https://galexthomas@bitbucket.org/accutechdev/bsu.finwellapps.git)
    

  

![](https://lh3.googleusercontent.com/Cph6_cNc342y1Ey0LP2VhJKev0E5GBDavv3lCnsbwPQKaWCKzJwdJXmjUyXYystmctQqFGYESy9ylGKoN5UmLOidGrZY3hgL8qCo8XVvlF8bqZ5ClL3CAt8o0133oiV0-uZwfLAG)

Once in Visual Studio, press clone repository.

In repository location, paste the url you obtained from the bitbucket and modify the path if desired. Next, press clone.

Once cloned, your file structure should look like this:

![](https://lh4.googleusercontent.com/Rz42XON5cO4pCQyglhVnTUUPijvWgHEMGwfWI42CxLUEb85y43lMsTjgU_FxnLhKdRHw_NDR9kc093uUtn1fRkFvn36ajZzOZViVkzbNXNORbDKNg1BlTCr8OlxdltqJQdOZ24tD)

Install NuGet on Visual Studio

Navigate to the Nuget Packet Manager by right clicking on the dependencies file and clicking on Manage NuGet Packages.

Once there click on the Installed tab and ensure that you have all of the shown packages downloaded. If not, you can install missing packages by going back to the browse tab and searching for them.

![](https://lh6.googleusercontent.com/fTJnzNzyV0im8TaZwca8wZ88ktfkcGSpZoYZDT7x849xYO6pQ36-gLT3aCZX2IL08qtsCnwCz5-cDuoXyY8eGAhoFT1IzZth04uTBVz5-yI5z5ZKxWwv4LClc-VCju0TrmcLK58L)

  

Install PostgreSQL version 13.1 using default options.

Link: [https://www.enterprisedb.com/downloads/postgres-postgresql-downloads](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)

Make a Postman account and install it using default options.

[https://www.postman.com/downloads/](https://www.postman.com/downloads/)

Install pgAdmin4 version 4.28 using default options.

[https://www.pgadmin.org/download/pgadmin-4-windows/](https://www.pgadmin.org/download/pgadmin-4-windows/)

### Building and compiling:

For PgAdmin4

1.  Open pgAdmin4
It is not uncommon for pgadmin to load endlessly upon first opening. To fix this issue you must open Registry editor. Withen that you must open the "HKEY_CLASSES_ROOT" folder. Within that folder is a subfolder labeled ".js" click on the folder name and change the "Content Type" to "text/javascript". Then restart pgadmin.
    
2.  Select “Add New Server”
    
3.  Give it a name of FinwellDB
    
4.  On the connection tab make the host “localhost”
    
5.  Set the password to whatever you want. But that password must match in step 4 of Visual Studio.
    
6.  Save the server created.
    

For Visual Studio

1.  Open Visual Studio
    
2.  Open FinwellAPI -> appsettings.json
    
3.  On line 11 change the “password=____” to the password created on step 5 in PgAdmin4.
    

Once those 2 things have been completed the program should be functional on your computer

### Final Result

If everything has gone correctly, running the program in Visual Studio should open a page on swagger. 
However it can be a common problem that it fails on the first try and works on the next attempt.
It should appear like this

![](https://lh3.googleusercontent.com/kdrDzWTQqllHxVrWu-fYvYQepfUD-z-Z-3ZX9zb1WVJKt7dR_4hYVoD7XQBSPbwoyuRF-ZOF2iY9Bkmv5tyla1yyws2iPngZOvKwweTpXzdJjykYnBAgdDetEXTk_jlDPl-HTv4D)

1.  Select the Income “GET /Income” button
    
2.  Change the media type to text/json on the drop down menu
    
3.  Press the “Try it out” button
    
4.  The return should look like
    

{

"income": 0

}

5.  Click “execute”
    
6.  It should then return with a “request URL” section with a result similar to
    

https://localhost:44388/Income

7.  Copy yours which likely has a different number after localhost
    
8.  Leave this tab open as we will come back to it later
    

Open Postman

1.  Select + New near the top left.
    
2.  Select Request
    
3.  Insert anything (We suggest “Test Request” for simplicity) for the request name
    
4.  Insert it or create a collection to put it into. (that name also doesn't matter)
    
5.  On the “Enter request URL” you should now paste the copied link from step 6 from the previous section.
    
6.  Select “Body”
    
7.  On the body page select the “raw” button
    
8.  Change the “Text” to “JSON”
    
9.  Go back to the swagger page and copy the following:
    

{

"income": 0

}

Section and paste it into the body Change the 0 into a larger number such as 200.

10.  Now click “Send”. The result should look like this:
    

![](https://lh4.googleusercontent.com/JnDk_2CTfzGmkij6xNaugTpC_mDKtObcTgGL6EcBtNygSNaJi43Z70mCCvrAWZtTMQz3V76pzEUg41vRVSIaeQ97NWRUTmjGzyzObDOTGebKEl5GtJo1rJU1ELcheJtfXQX9ArO-)

  
  

### Troubleshooting

Common errors include:

-   ECONNREFUSED, which occurs when the request cannot be sent from Postman
    

-   Go back to Visual Studio, and then make sure the program is running by checking whether the button has switched to a “Stop Sign”, which indicates that “Play” has already been pushed.
    

![](https://lh4.googleusercontent.com/6_FC6IyVz1UaH3Jx3J91XcxfWJMbhxtuCoPFX1w3rbE2DKn_vIRNc5rU5L-XOrFICl9WC3rvtbKo-dSd5FJemARhSFOF7reu7c63aXBtBDeqWhHz-NSKwSWKhzyDAjwIjGLP5d_9)

![](https://lh3.googleusercontent.com/KofZXt0XH0fYLYMdHnsRZ_DCQqEzhPJyvqRT_6yUN1V89Qp0Ne9Nd3vHQdl38_9RcvL1Z4g07hYNzfWefvYR_eRQswzN1GYy0g9gfPzZ3nacU5CmHagIfxP6OH5NAgez9b6vlfKW)

-   In pgAdmin, Make sure the database is connected by right-clicking on the database in the navigation section on the left hand side of the screen, and then clicking “connect”.
    

-   Connection string error, which occurs when your password is invalid.
    

-   Navigate back to FinwellAPI -> appsettings.json and making sure the password in line 11 is the password you created in pgAdmin.
