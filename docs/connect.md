# Connecting your ownCloud client to your ownCloud server

You can use ownCloud to share files and folders from your computer with other users and synchronize them using your ownCloud server. Once you place files in the shared directories on your device, these files are immediately synchronized with the server and with other devices using the ownCloud Desktop Sync Client, Android app, or iOS app. 

ownCloud has client applications for Window, OS X, and Linux desktops, and for Android and iOS devices. You can download the client that you require from the [ownCloud Web site](https://owncloud.com/client/). The application for mobile devices is available on Google Play and Apple App Store.

## Configuring your ownCloud Desktop or Mobile Client

Once you have installed the desktop client on your device, do the following to connect to your ownCloud server and synchronize your local files with the ownCloud server:

1. Launch the ownCloud desktop client.  
   This displays the "ownCloud Connection Wizard."
2. In the `Setup ownCloud server` screen, in the **Server Address** field, enter the IP address of your ownCloud server. 
3. In the `Enter user credentials` screen, enter the username and password of your ownCloud user account and click **Next**.
4. In the `Setup local folder options` screen, specify whether you want to sync all of your files or only selected files and folders on the ownCloud server.   
   ![ownCloud Connection Wizard - Setup local folder options screen](media/ownCloudConnWizardSyncOptions.png)  
   The default local sync folder, where you store the files that you want to synchronize with the ownCloud server, is located in your home directory and named `ownCloud`.  You can also change the default local sync folder.
5. Click **Connect** and then **Finish** to save the settings.   
   Once you click **Connect**, the client attempts to connect to your ownCloud server, and when it is successful, you will see two buttons: one to connect to your ownCloud Web UI and the other one to open your local folder. The client will also start synchronizing your files.

 