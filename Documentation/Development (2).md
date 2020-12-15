
# Tech stack:

#### The following technologies are utilized in this application. Before development it is recommended that you familiarize yourself with the documentation of some of the technologies, which you can find below:

[.NET](https://docs.microsoft.com/en-us/dotnet/)

[C#](https://docs.microsoft.com/en-us/dotnet/csharp/)

[Visual Studio Community 2019](https://docs.microsoft.com/en-us/visualstudio/windows/?view=vs-2019&preserve-view=true)

[Xamarin.forms](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/)

[NuGet](https://docs.microsoft.com/en-us/nuget/)

[PostgreSQL 13](https://www.postgresql.org/docs/)

[PGAdmin 4](https://www.pgadmin.org/docs/pgadmin4/4.29/index.html)

[Postman](https://learning.postman.com/docs/getting-started/introduction/)

  

## Packages:

[Newtonsoft.Json](https://www.newtonsoft.com/json/help/html/Introduction.htm)

[Microsoft.Extensions.Logging](https://docs.microsoft.com/en-us/dotnet/api/microsoft.extensions.logging?view=dotnet-plat-ext-5.0)

[Microsoft.Extensions.DependencyInjection](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-5.0)

[Microsoft.EntityFrameworkCore 5.0](https://docs.microsoft.com/en-us/ef/core/what-is-new/ef-core-5.0/whatsnew)

[Microsoft.AspNet.Mvc](https://docs.microsoft.com/en-us/aspnet/mvc/overview/getting-started/introduction/getting-started)

[Microsoft.AspNet.WebApi](https://dotnet.microsoft.com/apps/aspnet/apis)

[Moq](https://github.com/Moq/moq4/wiki/Quickstart)

# Replicating Development Environment

1.  Download Visual Studio Community 2019 Installer [here](https://visualstudio.microsoft.com/downloads/) and run it.
    

  

2.  In the installer, select these options from the workload and choose your installation location. Then, click install.![](https://lh3.googleusercontent.com/---ju60sevzin2Sk3k44JoGZ7Fr_pm4ZuzAzHWrdsrhIt-wiG18uAonz1b0qTRGWM77hqe9OdbzztE5b1wcHT3pYKtZffD47C4tRC7GdxHlm32sI9mci0Lc_1eKmn-HoRxP1nX4)
    

  

These workloads contain the dotnet core and mobile packages that you will need to download in order to build and run the project.

-   .NET desktop development
    
-   ASP.NET and web development
    
-   Mobile development with .NET
    

  

3.  Make an Atlassian account through Accutech by going [here](https://id.atlassian.com/).
    

Your Atlassian account is how you will access and clone the code repository for replication on your local machine.

  

4.  Once your Atlassian account is verified and you gain access to the repository, go to the Bitbucket page by clicking [here](https://bitbucket.org/accutechdev/bsu.finwellapps/src/master/).
    

  

5.  Press “Clone” in the upper left hand corner of the repository. Copy the link provided and you should be left with something similar to this: [https://{USERNAME}@bitbucket.org/accutechdev/bsu.finwellapps.git](https://galexthomas@bitbucket.org/accutechdev/bsu.finwellapps.git)
    

  

![](https://lh5.googleusercontent.com/A3uydZcG79ofkbth8Hhe6ZHWaAMhsovP6fCYP7DKOLFF7xwm7UZrzENa4WoVKuTUjD3Vtu4HsblgD7srMcpxxGdQCwff42kyT4GS3azUI43SJXAQsik7y7SVw_oTYnVEjUoJsSg)

Note

We recommend following the method below to clone the repository. Another method, however, is using the command line and the git clone .

Simply enter the below code into the command line

git clone https://{USERNAME}@bitbucket.org/accutechdev/bsu.finwellapps.git

  

6.  Open up Visual Studio, and press “Clone a repository” in the menu on the right side of the screen.
    

![](https://lh5.googleusercontent.com/VEN_REUG6VLIcVmyuEEThTXCSNpSyDPY-4WD1WmmDPpWdbEWjM2sGh8A3cW5oh-v5UuTtKTaZBcF1eaCViRUfgZ7T9QgCd4wHiWjI_eVsfO8fvyQ5Vxmo1KOxtHA2CpjS1DNUs0)

7.  In the “repository location” box, paste in the url of the repository. If desired, you may edit the file path, but we recommend keeping the default path. Next, press clone.
    

![](https://lh3.googleusercontent.com/q2edo2PfU3OpgW8Xvpc4h3QGrmR1BCbs0ENTQTc_8wNhoLPMnfDhQDzitar-luMIi4v2A8VTLT528CgGp5-2KX-OhCNMF91bkukZI6VbgdRRUffgjGY8vn24R7yZapO18kVjXs0)

  

It’s possible that you will be asked to enter your username and password after the repository will be cloned locally. If so, simply enter your Atlassian email and password that you created in step 3.

  

Wait for the repository to finish cloning— this could take a little while.

Once finished, your solution explorer should look like the image below.

If you don’t see your solution explorer, you can navigate to File -> Open -> Project/Solution… and find the folder in your file explorer where you placed the project. Clicking on Finwell.sln should open up the correct solution explorer and you should see the correct file structure.

![](https://lh4.googleusercontent.com/Vl_KM63ec2wUQ5t7OTZK8T49R-zQ0kNM6-EOAhhlZhCJxVLr797PnzzolQeDM0dWsTrSlSIe148mYu6OYlWl1XzBg2ZNW-UzOtFzvi4Ikg02YHRTTZL4VSBhPf0qcze0e4QMZvE)

For reference, the solution explorer should look like this:

![](https://lh5.googleusercontent.com/HOPf297__E8LKq3hE0Bz2NpULCOjcvNbC2Yo-DPk4pMHKic-mPRbNq5x62JJfPZ6f42Pq4p7OGPgQBv0CHH666suXkBc1rSLfY9U07yL5eiAwUdvQd3wh_gzalnFsYEqiVNvNjY)

  

8.  Navigate to the Nuget Packet Manager hovering over “Tools” at the top of the screen and press “Manage NuGet Packages for Solution…”
    

![](https://lh4.googleusercontent.com/DLT18UHlz0DMVFz0UZMK4jdUiWbI1RTbcXZGe2JAdMfn9IRWrTEAQXyAH97qCO0B7R4udTCPC0Hal9zLpqeX6IJskXpLqqfzHHOXF_RINWNCN_RCc1mD55FLN5LzDShTZavDfYc)

Once there navigate to the “Installed” tab and ensure that you have all of the shown packages downloaded. If not, you can install missing packages by navigating to the “Browse” tab and searching for them.

![](https://lh4.googleusercontent.com/_tNkBHxhdczyTOokTDir2LbJGzGhjk045QX40pTWIfPalxk20qRPYAql9EKNBzjOVuhMjI0_OMeMTI07KKp5EbRsOHJ5G1LJmgEyTA-pI3oFkYoGDXoMuItdSwE8uquSYIdsok4)![](https://lh5.googleusercontent.com/XoohuFZT8l9alnTZnDDNwaTrjKpRgIb25Xs8n2AfjEz7swLN_NTnoGcDp_zr3JbzGqsnNN1ixMtXeXWgM40vmL9dJP_yh0uLTH-yN4Jdk6TDKmv7Wt1JCp4yc_gPdJeRDF2E44Y)

9.  Next, install and follow along with the setup of each of these programs. For each of them, use default installation options.
    

  

-   Install PostgreSQL version 13.1 using default options by going [here](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads).
    
-   Install postman by going [here](https://www.postman.com/downloads/).
    

-   Keep in mind, to install and use postman you must first create an account.
    
-   Moreover, utilizing postman from the web is possible, but we find that using the desktop app is far preferable.
    

-   Install pgAdmin4 version 4.28 by going [here](https://www.pgadmin.org/download/pgadmin-4-windows/).
    

  

10.  Install your emulated android phone
    

1.  First, add the android toolbar to the top of your screen by navigating to View -> Toolbars -> and checking “Android”
    

![](https://lh3.googleusercontent.com/P8Mo0LXKxZE2C3TsJTQKqJ8jzY8XK3q2DmKimVsxlP2NLiFVRB5TMyRfuFfDBjBKRCfoI0EPpj3GqoFnYhUgotiysa58UcW1DutBF2-uIjbWvwW6qyE2Lvwx5-qTJd3pbrlPi84)

2.  Next, press on the phone icon on the Android toolbar to open up the Android Device Manager
    

![](https://lh3.googleusercontent.com/nCyx9vm8v0cAq9LipT1WI5PF7KLeeyIiIzsXSsw71srL4RyU53QWOy2Kq1G8d1pADkaqSGD4mHWKYJfyq4dbT6Mgh4VeZbJ9I88o0IldnV22DSI6q7_GFTPxPP9F0Xsr4xyqJ-M)

  

3.  In the Android Device Manager, press the “+ New” button at the top of the screen to add a new emulated device.
    

![](https://lh6.googleusercontent.com/Cib6CjDxBZSzemkHFjKIIeVXMka4EwFYepmtocsX7_Pj_kBluhrqIsoigbmVu1_Mom8wiOwzThb_ttJHLtBJtaK2BF_fA7B_p48TOltw0sip5Dy4GTSdegQEiSgoSRC9UhVdQVg)

4.  You will be greeted by the New Device screen. Here you can set the custom configurations for your emulated phone. You can customize this as desired, but the default configurations are acceptable.
    

General Tips:

-   If your emulator is very slow when it runs, consider increasing the amount of ram on the emulated device. It will dedicate more ram to the device at the cost of using up more of your pc’s ram.
    
-   Another way to speed up the performance of the phone is to decrease the resolution, decreasing the amount of pixels your computer has to render.
    

5.  Once finished, press create. Now, all of the files needed to create your emulated device will install. This could take a little while.
    
6.  Your emulated device should now be ready to test on. If you want, you can press the start button and test out the newly emulated phone.
    

  
  
  
  

Congrats! You have successfully replicated the development environment and are on your way to continue development on the Finwell Apps project. 😁

  

# Building the Projects

To build the different projects, find the project dropdown at the top of the screen. From here, you can switch between the different projects and build them individually.

![](https://lh4.googleusercontent.com/bq2lqGEUK7NvxhMmHTRjJwYiCKwEMj20BLyJ7-4qPXG04KtIceVZQy8Ri-re_hOE6_daN7NGfTE6qUV609Nr-x1WoPDSqhU_W1zo84r9LRxuVQi4UpwptMHDClpNnvqnEas5_PQ)

## Web API

To build the Web API, select FinwellAPI and hit the play button that says “IIS Express”. From there, you should be taken to the Swagger page that displays the API endpoints.

  

## Xamarin.forms

IMPORTANT: If you are using a version of Windows that is compatible with Hyper V (Professional, Education, or Enterprise) we strongly recommend enabling it for the best performance when using the emulator.

To enable Hyper V, press your Win key and type “Turn Windows features on or off”

In Windows features, scroll down to find Hyper-V and expand it.

Ensure all three boxes are checked. Next, scroll down and find Windows Hypervisor Platform and ensure it is checked.

![](https://lh5.googleusercontent.com/H8QivABUX5xWmXTusCZTu5psL1L1IZnWqH5WrNOimCyy8eIbExpH5pxMmDjFKLjm5s2u1lw6rbyM5-J0p8J27WoUEUEiP4jCt_ommKUg0ZTIdxIz9vVexw8roQW75V_8iS7Sf7A)

Alternatively, you can run the following command as an administrator on Windows Powershell

Enable-WindowsOptionalFeature -Online -FeatureName  Microsoft-Hyper-V -All

  
  

To build the Xamarin.forms project, select Finwell_UI.Android from the dropdown and you should now see the device that you created in place of the green “IIS Express button”.

Note

If you don’t see it, try selecting it from the dropdown at the side of the play button.

  

Hit play on the name of the device you created, and the phone should be pulled up automatically and run the application.

  
  
  

## Testing

The tests in our application cover the mathematical calculations used in creating a simple budget and the business logic of the API.

To run the tests, navigate to the top of the screen and hover over the “Test” button. From there Test -> Run All Tests

Once you have pressed Run All Tests, every test should run and report as to whether it passed or failed.

![](https://lh4.googleusercontent.com/WI05tjXtUtqt_yNuaA-K0q_q5_Z3PfdYDFI8G4AY4kTnvCg5OKLsfQ6YbCr6hwYyLjgXWCwt_-7gTurx0Ha2stRSUVA9MGU3KCzCk9mCDnoJpLcTVc7WKHrRGZLRKDCv7rHArCA)

Above is an example of the output of the testing report from the Visual Studio.

  

## File and Folder Structure

Currently there are six projects in the FinwellSolution solution explorer that makes up our project as a whole. Three of these (Finwell_UI, Finwell_UI.Android, and Finwell_UI.iOS) are used to create the frontend application to deploy natively to Android and iOS phones. FinwellBackend handles the business logic of our project; it contains the logic for building and creating budgets, as well as savings goals, categories, etc.

FinwellAPI implements the API that we are expecting to use in unison with the frontend application in later iterations. In this current iteration, we do not have a way to host the API for the application to pull from, but this issue will be solved in future iterations. \

The final project in our application is FinwellApp.Tests, which contains all of the various unit tests for our application.
