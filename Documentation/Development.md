# Development

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
    

  

2.  In the installer, select these options from the workload and choose your installation location. Then, click install.![](https://lh6.googleusercontent.com/JZVPhGlpvQ4lm3wybtU9K2heEuF1wq2j29N4OTud7sT2npHiQxn6PxTGJ1T45J5F9vK1td7eQMVqOBmv36sjyqc1VnR1rCoIgNWdsks2DzlXNzUh_ts6eVnBmpgKVNxsPkHixF2j)
    

  

These workloads contain the dotnet core and mobile packages that you will need to download in order to build and run the project.

-   .NET desktop development
    
-   ASP.NET and web development
    
-   Mobile development with .NET
    

  

3.  Make an Atlassian account through Accutech by going [here](https://id.atlassian.com/).
    

Your Atlassian account is how you will access and clone the code repository for replication on your local machine.

  

4.  Once your Atlassian account is verified and you gain access to the repository, go to the Bitbucket page by clicking [here](https://bitbucket.org/accutechdev/bsu.finwellapps/src/master/).
    

  

5.  Press “Clone” in the upper left hand corner of the repository. Copy the link provided and you should be left with something similar to this: [https://{USERNAME}@bitbucket.org/accutechdev/bsu.finwellapps.git](https://galexthomas@bitbucket.org/accutechdev/bsu.finwellapps.git)
    

  

![](https://lh5.googleusercontent.com/poTroQMy8LqUEMPgAxZ8Czzghk9g7tI--bG6kxZTUWL9xkcwxXTcL9m4knVa5y4msoYscktssQ2flt2NSa-YiPXyYYtMWTfDpsJEyagAxKWV-kceezqVoBppoEsQv1wYbELjUDOY)

Note

We recommend following the method below to clone the repository. Another method, however, is using the command line and the git clone .

Simply enter the below code into the command line

git clone https://{USERNAME}@bitbucket.org/accutechdev/bsu.finwellapps.git

  

6.  Open up Visual Studio, and press “Clone a repository” in the menu on the right side of the screen.
    

![](https://lh3.googleusercontent.com/0hCPcwcI-zkhBahYWziew3xlNVYtQlTG4MgyUtuzEbXJnCNVqySEmFJPD8yMGqExxTFV1xz_bKWerWuMRvNwtuGoTT58zQr87URzA_0urrLpIF5yu4DQaa0w1_QB1WBWw8uBP_8o)

7.  In the “repository location” box, paste in the url of the repository. If desired, you may edit the file path, but we recommend keeping the default path. Next, press clone.
    

![](https://lh5.googleusercontent.com/PyyDgs9_UTnFI7LgRB2OXxv5BvfgGlMpd9d81xDnP-XAO-I9HIQYNBLnhpAfcoOndp-PlUyaXbuOm5_PuZEw7KA32E7nnWCWHSaNiyW5Ii1etlp679CJyt4LM5ZH0uxO6Mlxssbs)

  

It’s possible that you will be asked to enter your username and password after the repository will be cloned locally. If so, simply enter your Atlassian email and password that you created in step 3.

  

Wait for the repository to finish cloning— this could take a little while.

Once finished, your solution explorer should look like the image below.

If you don’t see your solution explorer, you can navigate to File -> Open -> Project/Solution… and find the folder in your file explorer where you placed the project. Clicking on Finwell.sln should open up the correct solution explorer and you should see the correct file structure.

![](https://lh6.googleusercontent.com/hsUCocdWwNipjyHIk9Kkmo45M-nGFV-rO2qC3gzTNCyfcrLUbQ-53hNe9Ol2SHozbGHs82bSVMR0WwVIKnB7UWYAqqwZhCGDvFQUXtZ-6_wygS9IYeeeU_017yDha8L3b3y0x-vu)

For reference, the solution explorer should look like this:

![](https://lh5.googleusercontent.com/Leqfq99u93ZOaHaZADdgf6NfzFbjybGzNxdhrt1PNgOGQuaOYK-jXj_FwPyntfM_P8BPiZ7l1dHk3Vgnt2LshGosidbpHS1l8BWtq-rKN2SHCuP7ihC5O1VSVDudSeEHx_e-AqAX)

  

8.  Navigate to the Nuget Packet Manager hovering over “Tools” at the top of the screen and press “Manage NuGet Packages for Solution…”
    

![](https://lh4.googleusercontent.com/6pxFZB-YKydkCA3MDq8_0IMtuVZ7ezr_YjkqPtmiHuyC8QaQ3Raw1bZI7B_12S63qthVo7SjmDyqa-BKSkGe-ezo9xBI81QC5OHXmXU2-GHU6c5gBBS4HUUedFctKGLLTm6E138O)

Once there navigate to the “Installed” tab and ensure that you have all of the shown packages downloaded. If not, you can install missing packages by navigating to the “Browse” tab and searching for them.

![](https://lh3.googleusercontent.com/he-ru8nyKzr0TbDFBn_Nou6fTwyGZLkpIzznwV_JSKRfD2RjP1bQuyPQZpj8Dkf17GGpeBbTMazod90_fKyHZhGfTfOQlSK8FqUqgSFV4JTt9-ahSBtX-Qh49dnZsFWhbCFijfVy)![](https://lh3.googleusercontent.com/S7rlS0W_4UKtxCVf60QZTVL1ebjddZhsrGmuvyLtLQwQ9j-gDpLcAs7WX7QVzcIMNtXq_TY_nhBMJc5AMLSBuSU1SaoCxmfQzYUWSjehLCvfWpysqUH51vuPRo-rfPDkIXCokEVQ)

9.  Next, install and follow along with the setup of each of these programs. For each of them, use default installation options.
    

  

-   Install PostgreSQL version 13.1 using default options by going [here](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads).
    
-   Install postman by going [here](https://www.postman.com/downloads/).
    

-   Keep in mind, to install and use postman you must first create an account.
    
-   Moreover, utilizing postman from the web is possible, but we find that using the desktop app is far preferable.
    

-   Install pgAdmin4 version 4.28 by going [here](https://www.pgadmin.org/download/pgadmin-4-windows/).
    

  

10.  Install your emulated android phone
    

1.  First, add the android toolbar to the top of your screen by navigating to View -> Toolbars -> and checking “Android”
    

![](https://lh5.googleusercontent.com/uwdtqMedvWZXhLsosQa2_Rfw5fyftEJkhHqGDiGwMbCJ5Wg9yUOHZUlNIv-wM5cvfnZxLhijuqqHcZIT64o1xN2Vfv2BsRTogAF0byVZtnuc1E4khYz7wavrB-f4PDLbh546YTYT)

2.  Next, press on the phone icon on the Android toolbar to open up the Android Device Manager
    

![](https://lh3.googleusercontent.com/l5fo0HGOTAY_tZDSr3hSaJ9TmsD1Ad3xn2iHR7mp6heNOT7WAGr7sHxamCFQ3c8ScShgY5xVaV0xCBIAQHdfKsGck3TrlFICkLm8t4-fETKDi3ZX7SVwP0QoJcTQllo_TFGhJlYT)

  

3.  In the Android Device Manager, press the “+ New” button at the top of the screen to add a new emulated device.
    

![](https://lh3.googleusercontent.com/6PkOrwkvIycgci99QwkbyOIVQPnFXgo758JJygrQ7E3T78VCg0JHkORvjekBF--jw-DGY3hF_m3vcj6kUFaMkeaWEVTv8PbvkLcuP08Wl2xy7EJnnzaa-nD6TJNPfGTDqt51_J5P)

4.  You will be greeted by the New Device screen. Here you can set the custom configurations for your emulated phone. You can customize this as desired, but the default configurations are acceptable.
    

General Tips:

-   If your emulator is very slow when it runs, consider increasing the amount of ram on the emulated device. It will dedicate more ram to the device at the cost of using up more of your pc’s ram.
    
-   Another way to speed up the performance of the phone is to decrease the resolution, decreasing the amount of pixels your computer has to render.
    

5.  Once finished, press create. Now, all of the files needed to create your emulated device will install. This could take a little while.
    
6.  Your emulated device should now be ready to test on. If you want, you can press the start button and test out the newly emulated phone.
    

  
  
  
  

Congrats! You have successfully replicated the development environment and are on your way to continue development on the Finwell Apps project. 😁

  

# Building the Projects

To build the different projects, find the project dropdown at the top of the screen. From here, you can switch between the different projects and build them individually.

![](https://lh6.googleusercontent.com/DZKwYRCXVJ9HuooYtkdnbAAa3r6d6eBq1vEEZc2jp3JHNNOqU8-RBD-9LFiZjbDnvkqDmJTKMSSuKBR2s4AkTS8dD_BYVvSH-XlXau9dsSUwogx6C31kC1N03z0nffel1LXi7TZy)

## Web API

To build the Web API, select FinwellAPI and hit the play button that says “IIS Express”. From there, you should be taken to the Swagger page that displays the API endpoints.

  

## Xamarin.forms

IMPORTANT: If you are using a version of Windows that is compatible with Hyper V (Professional, Education, or Enterprise) we strongly recommend enabling it for the best performance when using the emulator.

To enable Hyper V, press your Win key and type “Turn Windows features on or off”

In Windows features, scroll down to find Hyper-V and expand it.

Ensure all three boxes are checked. Next, scroll down and find Windows Hypervisor Platform and ensure it is checked.

![](https://lh3.googleusercontent.com/UmiNQeu6jhyejQTVbFPLKoZ7-6lQw8zJ5l8iOiNZLE3gGKkF1WtKnvRyLtadlFMYM5NWOSHKtvppgJ3Q_U0AxaEiyV5DwzNvUR-Gl2VO9yq6SvVkk7djQZvNGCiVz3bhxBevOf0w)

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

![](https://lh3.googleusercontent.com/q-09xBN7azcY5jPmIlQ2OzmnUrT8nGWY6vUsWghRkYy9QyprCYqRDUKDTEq6YM4LMzuRCPL6xdaKUIy7L2vq_jz84e1bogGMtDs3YM32Dhgfn7FeMCjE0Sd_aBWNaDYzqY7Apsm-)

Above is an example of the output of the testing report from the Visual Studio.

### UI Testing

First to set up UI Testing you need to set 2 Environment Variables if they are not already set. These include the ANDROID_HOME variable and JAVA_HOME variable. Pointing to the android SDK and java jdk respectfully. Look below for an example image.

![](https://lh6.googleusercontent.com/n_Gd-rq5XeBPw_C7rqz7C-0pQqTTpwn5uRjdQAYXH55Msh6sgnwn0zlIi8nq598vwyge6BRWWfhvF7w2dKeMzjTgcOQb149jNRTPpGQ_BlwSmHsSpKUvzrjJUCIK28zb7N9Ezez4)

Second you need to run an android device on the release build such as the one seen below. We suggest Pixel 2 Pie 9.0 running API 28. This is because some of the testing methods are broken for certain Android devices. This is a fault of the package developer, and not the actual testing code.

![](https://lh4.googleusercontent.com/lQa4MIGtgi7i5HF76tKs03myNl_c6ghdxwalLEJULKt7LKxkCGKrAcrENY6qhAyad7VT6Ztt3hDk0gG_m-bo25keG9eAJ4MXs7wZBKcMx3oQ8dmVfbp1GEsAFyg8Nq9HtRZ6UeEP)

Once you have successfully launched the emulator in VS a file will be created locally in your project. Below is the example location.

![](https://lh6.googleusercontent.com/OpKTHi2HhSEwD_78NfGEceWQtIPLkIpxzhFLxU1WSOWAGNPnPeedUQpVZH8Nh3C0-4xGJ6XhjTceCz0VwwlAjZJ4aHB9f0uC1W7wC7HhLLKABJaR5_11X0vDm5LxXr9vXWLF33d8)

The highlighted file is the one you need to reference inside your app initializer. Copy this file location and it will be used in the final step.

Finally open up the app initializer and change the apkFile link to the one you copied (Seen on line 13)

![](https://lh4.googleusercontent.com/EMc8AFkvGg3QotVeeGCiPlRVDC9Ev8yuX-eDAh5x1gL0aeDQ5AbKnCXRDf4nMPZhj4nQPeowlTrp_n8-EUYNeU5P6xMZZy16nueyI6YdmcM1tVpnKR1OnTZ1wJM1Vmfg6nTaMD5n)

After all that has been completed, rebuild the project and run the emulator. The emulator must be running when you run the tests.

When running the tests you should be able to see them perform the actions in real time. This can be slow, so only certain tests after having made any changes that need testing.

Its important to note iOS tests are not expected to pass. You can not get them to pass unless you have an iOS emulator or some other MAC device. (Getting an iOS emulator for testing something that should be identical would be a waste of time). Below is a picture of the expected results.

![](https://lh3.googleusercontent.com/Nj8bgbKVKdtfnpY6FpMfMJzK_IrvSaa8_Hc9L1vMZaIDdYT2jdi4Pv8Ajzi1_jY6Q-Ool6_eOAcXRoUXxt8e1-CMHDZUXGZyUNVQv1l3-M8JcPmjeV_8WMYEul3_qLyS1kN8w20Y)

## File and Folder Structure

Currently there are seven projects in the FinwellSolution solution explorer that make up our project as a whole. Three of these (Finwell_UI, Finwell_UI.Android, and Finwell_UI.iOS) are used to create the frontend application to deploy natively to Android and iOS phones. FinwellBackend handles the business logic of our project; it contains the logic for building and creating budgets, as well as savings goals, categories, etc.

FinwellAPI implements the API that we are expecting to use in unison with the frontend application in later iterations. In this current iteration, we do not have a way to host the API for the application to pull from, but this issue will be solved in future iterations. FinwellApp.Tests, which contains all of the various unit tests for our application. And lastly UITest will only include testing for the user interface which takes mu
