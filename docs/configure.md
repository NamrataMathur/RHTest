# Configuring ownCloud 

To access the ownCloud web interface, open a web browser and type `https://server_domain_or_IP/owncloud`, where IP is the IP address of your ownCloud instance.

You should see the ownCloud web configuration page in your browser: 

![ownCloud Login Page](media/ownCloudLoginPage.png)

Create an admin account by typing a username and password and then click the **Storage & Database** link. Leave the **Data Folder** setting unchanged and click the **MySQL/MariaDB** option, and enter the database information that you have configured previously. 

![Creating an admin account](media/ownCloudLoginConfig.png)

Click **Finish setup** to sign into to ownCloud and open the Web UI of ownCloud:

![ownCloud Web Interface](media/ownCloudMainUIPg.png)

Administrators can manage users using the user management page of the ownCloud Web UI, and once administrators configure user accounts, they also will be able to access ownCloud using the `https://server_domain_or_IP/owncloud` URL, where IP is the IP address of the ownCloud instance.

For detailed information on configuration of ownCloud, see ownCloud Administration Manual - Configuration](https://doc.owncloud.com/server/admin_manual/configuration/).
