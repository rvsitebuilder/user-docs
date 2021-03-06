# Installation


- [Control Panel Installation](#control-panel-installation)
- [Web Installation](#web-installation)

## Control Panel Installation

RVsitebuilder 7 can install on control panel system by server administrator. If you don't own a server you can find one from our hosting partner below.

1. You can buy hosting service from our [hosting partners](https://rvsitebuilder.com/hosting-partner/) to get a control panel account with RVsitebuilder that's already installed.

2. Then you can access to RVsitebuilder immediately from [your control panel](website-design.md#create-a-new-site) and start your website!

## Web Installation

RVsitebuilder 7 can also install on every domain name. **If you have a Host Provider who provides you a control panel account by Control Panel Installation above. You don't have to install it by yourself and can ignore this.**

1. Get a domain name on a server that already has RVsitebuilder license from your host provider or find one in our [hosting partners](https://rvsitebuilder.com/hosting-partner/) list.

2. Make your domain configuration meet with the following requirements.

   - Domain name must run on PHP7.1.3 or above.
   - php extension: 'mysqlnd','pdo','gd','curl','iconv','mbstring','zip','posix_getpwuid','json'
   - php ini config 'memory_limit' => 64M
   - Firewall on your server doesn't block the following domains.  
   download.rvglobalsoft.com  
   Files.mirror1.rvsitebuilder.com

3. Create a database, perform the following steps to create the MySQL database.

   1. Click icon to create MySQL® databases.

      ![image](images/install_nocp/create-db-step1.png)

   2. In the New Database text box, enter a name for the database and click create database.

      ![image](images/install_nocp/create-db-step2.png)

   3. A new interface will appear. Click Go Back.

      ![image](images/install_nocp/create-db-step3.png)

   4. The new database appears in the Current Databases table.

      ![image](images/install_nocp/create-db-step4.png)

**After you created a database, add users to the database and configure their privileges. To create a new user account, perform the following steps:**

1. Enter a username in the Username text box.
2. Enter and confirm the new password in the appropriate text boxes.
3. Click Create User.

   ![image](images/install_nocp/create-db-step5.png)

4. Click Go Back to return to the main interface.

   ![image](images/install_nocp/create-db-step6.png)

**Add a user to a database. To add a user to a database, perform the following steps:**

1. In the Add User To Database section of the interface, select the desired user and database from the menus. Click Add.

   ![image](images/install_nocp/create-db-step7.png)

2. Select the checkboxes that correspond to the privileges that you wish to grant to the user. Click Make Changes. And click Go back to return to the main interface.

   ![image](images/install_nocp/create-db-step8.png)

3. Download RVsitebuilder Setup wizard

   1. Download RVsitebuilder Setup wizard https://files.mirror1.rvsitebuilder.com/download/rvsitebuilderinstaller/setup to your local computer.

   2. Click botton `Upload`.
   
      ![image](images/install_nocp/upload1.png)

   3. A new interface will appear. Click selete and choose file download RVsitebuilder Setup wizard.

   4. Waiting a progress bar can show a complete state. 100% . And click Go back to "/home/mydomain/public_html"

      ![image](images/install_nocp/upload2.png)

   5. Right click and choose `Extract` the setup file to "/public_html"
   
      ![image](images/install_nocp/upload3.png)
      ![image](images/install_nocp/upload4.png)

   6. completed.

      ![image](images/install_nocp/upload5.png)

4. Install RVsitebuilder directly on your domain name.

   1. Call the setup.php script for your domain name on browser http://mydomainname.com/rvsitebuilder/setup.php

      ![image](images/install_nocp/Install-nocp-step1.png)

   2. Database and FTP setup

      ![image](images/install_nocp/Install-nocp-step2.png)

   3. website properties setup
   
      ![image](images/install_nocp/Install-nocp-step3.png)

   4. Accept agreement and install.

      ![image](images/install_nocp/Install-nocp-step4-1.png)
      ![image](images/install_nocp/Install-nocp-step4-2.png)

5. Once the installation is completed.
   RVsitebuilder CMS is ready to [create website]((website-design.md#create-a-new-site) on your domain now!

   ![image](images/install_nocp/Install-nocp-step-login.png)