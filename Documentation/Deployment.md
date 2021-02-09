## Deployment

Note

Because our application does not currently have an executable or APK to distribute for this iteration, those wishing to deploy our application will have to clone the repository. You can find the steps for doing so below.

  

The current iteration of our application deploys only the frontend of our application as we lack a server to host our API from, and mobile phones are unable to use localhost to access the API endpoints. As such, the deployment documentation for this iteration omits the API deployment for the time being. In future iterations, the API deployment will be covered when it is utilized by our Xamarin application. For now, the Xamarin application saves locally using SQLite.

  

# Replicating Development Environment

1.  Download Visual Studio Community 2019 Installer [here](https://visualstudio.microsoft.com/downloads/) and run it.
    

  

2.  In the installer, select these options from the workload and choose your installation location. Then, click install.![](https://lh4.googleusercontent.com/wF_NxaxA3oUTGIyx7F30QuQJbrKsbe_QrijDkHKkoDu5QLRaMdrDtw7mjb7miKiBKg-tgJZNTBb-VFQqMi8RKUcTl1DNjQgw2q5BtMf4Ad20gAkFrriE2ucE9ZtL2fzftOnaA8Q)
    

  

These workloads contain the dotnet core and mobile packages that you will need to download in order to build and run the project.

-   .NET desktop development
    
-   ASP.NET and web development
    
-   Mobile development with .NET
    

  

3.  Make an Atlassian account through Accutech by going [here](https://id.atlassian.com/).
    

Your Atlassian account is how you will access and clone the code repository for replication on your local machine.

  

4.  Once your Atlassian account is verified and you gain access to the repository, go to the Bitbucket page by clicking [here](https://bitbucket.org/accutechdev/bsu.finwellapps/src/master/).
    

  

5.  Press “Clone” in the upper left hand corner of the repository. Copy the link provided and you should be left with something similar to this: [https://{USERNAME}@bitbucket.org/accutechdev/bsu.finwellapps.git](https://galexthomas@bitbucket.org/accutechdev/bsu.finwellapps.git)
    

![](https://lh6.googleusercontent.com/xmWUNblmr-9yBlVRADCnlSd8EIv9pf2-qv3ldo3iCVfDu3MxueIFMPzqqzafi4UXi2z6Zu9p0Efjnh_3yv3I-K0VOt0nGrSreyjfo66Twuk58Zfj6GYpwyBYQonvDL3UDL6vWnE)

Note

We recommend following the method below to clone the repository. Another method, however, is using the command line and the git clone .

Simply enter the below code into the command line

git clone https://{USERNAME}@bitbucket.org/accutechdev/bsu.finwellapps.git

  
  

6.  Open up Visual Studio, and press “Clone a repository” in the menu on the right side of the screen.
    

![](https://lh5.googleusercontent.com/DFVx_kOq0gpbmiPcZhehbPw3-Unf41KoCKiPXD0xim1WZlV3UuOfm4gqLNO3h0H5VGTaZC6HfOdBKTDNPmqGWIrU_w4jbXykVK8JulcAXXPit7mGpcNWXJyeC3gqxYueqxhrgBk)

7.  In the “repository location” box, paste in the url of the repository. If desired, you may edit the file path, but we recommend keeping the default path. Next, press clone.
    

![](https://lh3.googleusercontent.com/4vCc31YisNHThRkb9qJ88C1rryNK4EXyYGO1hcFtWuSj6bEExYkn9i3OwNjbQ9rlrYCTbb2OismbCSrSMXjjrjujiv0Y9wlfZTK6Zuw0FcLbCysL-yYNDt9ECFwluk4S2PD54IQ)

  

It’s possible that you will be asked to enter your username and password after the repository will be cloned locally. If so, simply enter your Atlassian email and password that you created in step 3.

  

Wait for the repository to finish cloning— this could take a little while.

Once finished, your solution explorer should look like the image below.

If you don’t see your solution explorer, you can navigate to File -> Open -> Project/Solution… and find the folder in your file explorer where you placed the project. Clicking on FinwellSolution.sln should open up the correct solution explorer and you should see the correct file structure.

![](https://lh5.googleusercontent.com/Nl1NQ-Q5aJQELLlvqgNoafHFocoFt-8GNXT3qxnLI_PoEHbsVgK4IrkWZTOQpm7b_5XW0lYn9s7vpWAVweI20j3cau7b2f8BO-BdHBNu2JisX08Eyegagkm2Sb2lW5h9zF8AvEU)

For reference, the solution explorer should look like this.

Note

You shouldn’t have to personally modify any files either in the solution explorer or Windows File explorer.

Use the below files for reference, though, if they get misplaced and need to be put back into order.

![](https://lh3.googleusercontent.com/wXzb47nRWBeIIv5MpxxIFs11zGtzdIJZnx6uG-ouGw-oxCjAy_jb5tCQ6zpFrVBNA_FnLES2-_VrTKO_jtRxW4j018iZ2cZ6juytiT-_YtWdNFvpCW3bBjdm1i9xKd3qlzEiCsg)

  

![](https://lh4.googleusercontent.com/pnUdyhCa9gJDMI0GRV6dRgLWKCZZ71OLpQySrn8M-1mZdMWXwnB1XvccN4B6PW_5OF--zxuT9naWTcGWIHrRTmgt1vgewJZdXY74mdoGqmOc5QfsmsjsIlXd4dIwWySYewOG640)

  

8.  Navigate to the Nuget Packet Manager hovering over “Tools” at the top of the screen and press “Manage NuGet Packages for Solution…”
    

![](https://lh6.googleusercontent.com/lrthiwC6q7edKjrnv_9f_BAaLINdMThF9rmIfH06jUjrxTRGg12Gzq8Q8q7Ikp0Xc_eu2j5v2Xer_iB3a0tpac_iPractpIdvi057osCpokh2HRhZugRLvGxGYyvHrvuW5XkoLw)

Once there navigate to the “Installed” tab and ensure that you have all of the shown packages downloaded. If not, you can install missing packages by navigating to the “Browse” tab and searching for them.

![](https://lh4.googleusercontent.com/2yNGTgTPpWFBLRPenXNtKcaQSf9We_xY1eGNq61U6DEyBPF5vPrIXNFz0sgoVzwrf9te36M5UscwX282ECWchpeZ32fFaeKq3PUM99YeMCfvWRNv1Z9WFrh1kxF2EBRTJ97mTiY)![](https://lh6.googleusercontent.com/fxQxNAt5AasBrNFNjJ6p8fNPxAS6gqri2-q2KGLyhyr0AwdGGYCJ73bLJ8PHQf48ZaLcbEmGyiP_VnafRyETfFGNTNZtk45btNusgoNV998Nihj29WolIA0Ew-QrSrMjjtQ_UR4)


9.  Install your emulated android phone
    

1.  First, add the android toolbar to the top of your screen by navigating to View -> Toolbars -> and checking “Android”
    

![](https://lh3.googleusercontent.com/ih0gSgep0l9I6Y5PRfR4vXSM47fHK0COJOSH5W0pD_PvEK9605O4NvCaM86iTK8XPy-ySLbe2W-DRi1JfypI1RA4XUl9dIqIuEG-SWUb1sF30DXHBgzJDmZe9nRbA1SyolK92_U)

2.  Next, press on the phone icon on the Android toolbar to open up the Android Device Manager
    

![](https://lh4.googleusercontent.com/VBmlgyBP7COJJV7iv1DpYHP1UqaMt8QqPANjIgRGJixj0oIun3FS7Uf_r2OPRKl1KNa4xKfXod1IJNyoIcVkOupj3IoN28GlIpcC5Nk5NqC_wYQCKD-7LkPJ1iNscfHNgKUX9Bs)

  

3.  In the Android Device Manager, press the “+ New” button at the top of the screen to add a new emulated device.
    

![](https://lh3.googleusercontent.com/M3fYGt6Ya1e6xQ4okrkqaLpYnTGQijWb6Ki6PzO8w36CI2wWQTq8209_dEHjGc2yYJo78NrItY6USntSvwHIq7EkBpV_fROthSBVsU-SlQXTqe9C2UuI9axK1n_Xm3pSBY7kGtA)

4.  You will be greeted by the New Device screen. Here you can set the custom configurations for your emulated phone. You can customize this as desired, but the default configurations are acceptable.
    

General Tips:

-   A large performance boost will result from using and enabling Hyper-V. However, this is not possible on some versions of windows. More is explained further below.
    
-   If your emulator is very slow when it runs, consider increasing the amount of ram on the emulated device. It will dedicate more ram to the device at the cost of using up more of your pc’s ram.
    
-   Another way to speed up the performance of the phone is to decrease the resolution, decreasing the amount of pixels your computer has to render.
    

  

5.  Once finished, press create. Now, all of the files needed to create your emulated device will install. This could take a little while.
    
6.  Your emulated device should now be ready to test on. If you want, you can press the start button and test out the newly emulated phone.
    

  
  
  

Congrats! You have successfully replicated the development environment and are on your way to deploying the Finwell Apps project.

### Building and compiling:

## Xamarin.forms

IMPORTANT

If you are using a version of Windows that is compatible with Hyper V (Professional, Education, or Enterprise) we strongly recommend enabling it for the best performance when using the emulator.

To enable Hyper V, press your Win key and type “Turn Windows features on or off”

In Windows features, scroll down to find Hyper-V and expand it.

Ensure all three boxes are checked. Next, scroll down and find Windows Hypervisor Platform and ensure it is checked.

![](https://lh6.googleusercontent.com/OXPNxAyjCMS7vUqJ8jPfc1w5fU_mSRhkFIyNJIgwLk26YK69otfAWOpwnoNU6Bi44OPicJiFe-sTkfdXFL2MgolBg0xugm-RzPA3IScnLEXiUTOuS-9SCwdAepL-_PDShGIC0rA)

Alternatively, you can run the following command as an administrator on Windows Powershell

Enable-WindowsOptionalFeature -Online -FeatureName  Microsoft-Hyper-V -All

  
  

To build the application, first ensure that you have your emulated phone ready to use that we created in the previous section.

Your play button should look something like this, but the name will vary in accordance with what you named your phone.

![](https://lh3.googleusercontent.com/ZEHV6NDS1MVPLTXWVgtdsy2s49FYuBLBx-6joiQtHDTxZsHK4xyTPS9J8pVpLSbSmfJCrVgyA_3XewA94bI-wUe4GH8Ma-Hp3kKY1_tlAaeuFzXzaOO8puntqaSBP8_aSA6NmfY)

Note

We have found that it is possible that Visual Studio 2019 still warns you about using Hyper-V regardless of whether it is enabled or not. If you see a warning about Hyper-V, we recommend going back to the previous section and following the enable Hyper-V steps to ensure that it is enabled.

Press the play button, and your Android test phone will automatically start up and load the program!

The time it takes to pull up the emulator and run the application is based on a number of factors, but these have the largest impact:

-   The power of your pc
    
-   Amount of ram you dedicated to your emulated device
    
-   The screen resolution of your emulated device
    

Now, to stop the program simply press the red stop button at the top of your screen.

![](https://lh3.googleusercontent.com/0cx_Dai-r0BzKnW3HtXRd-03DA7XPPv-k8YzqZ6LL7k4qto_W5JOBfsinFGzjYs-NWSadn15zN9VwtUJvPJKjVPpdXd9_XPEJOrfOnPKDCaCqSc75RdvNE3JXy6BdtEHnwRhLO0)

### Troubleshooting

Hopefully, by following the steps above you are able to get the application deployed and working. However, sometimes technology doesn’t work the way we want it to. Here are some of the most common problems we have run into when building and running the application.

Note

If you run into any issues or errors during your build or deployment, they will be logged in the output debug console in Visual Studio. Here, all of the errors in the program will be displayed.

  
This console will display the error and the location in the code where the error took place. To be taken there, simply right click on the error -> Go To Location. This is the easiest way to find out exactly what and where failed when trying to build the application.

  

Many of the problems that we have run into relate to the performance of the emulator:

  
  

If your Android device shows the "Storage space running out" error message and runs very slowly, there are a few different things you can try.

1.  Firstly, you can add more sd space to the phone.To do this, navigate to the Android Device Manager and right click on your created device -> Edit. Next, increase the value of the SD space in the manager. This will allow the emulated device to have more space at the cost of utilizing more space on your pc.
    
2.  Factory reset the device: To do this, navigate to the Android Device Manager and right click on your created device -> Factory Reset
    
3.  If the above method doesn’t work, try deleting the device and creating a new one.
    

  

The above methods should solve the “Storage space running out” issue.

  

If your emulated device still runs slow, we would recommend enabling Hyper-V if you have not already. To do this, look back at the Enabling Hyper-V section in this manual.

  

Another way to increase the speed of your device is to upgrade the virtual components on your emulated device

  

To do this, navigate to the Android Device Manager and right click on your created device -> Edit. Once in the device manager menu, to increase the performance of your emulated device do any or all of the following.

  

 Note

The following methods can help to speed up your emulated device at the cost of using more of your computer’s resources.

Be warned, if you increase the values too much you can risk your computer running very slowly or freezing altogether. It is best to implement changes incrementally to avoid drastic differences in performance.

  

-   Increase the amount of RAM on the emulated device
    
-   Decrease the amount of resolution on the emulated device
    
-   Increase the amount of cores on the emulated device the app: all of your budget categories will still be there when you return! 
