##### **1. Download MySQL Installer**

- Go to the [MySQL official download page](https://dev.mysql.com/downloads/installer/).

  ![image-20240821210938203](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821210938203.png)

  ![Uploading 联想截图_20240821152914.png…]()
![Uploading image.png…]()


- Select the Community Edition for download.

  ![image-20240821211216081](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821211216081.png)

- Select the "MySQL Installer for Windows".

  <img src="C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821211424283.png" alt="image-20240821211424283" style="zoom: 50%;" />

- Select the second one and start the download.

  <img src="C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821211512391.png" alt="image-20240821211512391" style="zoom: 40%;" />

  

  <img src="C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821211844176.png" alt="image-20240821211844176" style="zoom:50%;" />

- You will get an installer file(`.msi`).

  ![image-20240821155641211](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821155641211.png)



##### **2. Run the Installer**

- Double-click the downloaded installer file (`.msi`).

  <img src="C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821205112834.png" alt="image-20240821205112834" style="zoom: 67%;" />

- Choose the “Server Only” installation type, then click **Next**.

  ![image-20240821215953249](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821215953249.png)

- Once you select the products, you click the **Next** button to continue.

  ![image-20240821220116443](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821220116443.png)

- The MySQL Installer will download the selected products from the internet. Please ensure you have an active internet connection and wait for a few minutes for the download to complete.

- After the download is complete, click the **Execute** button to start the installation.

  ![image-20240821220336026](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821220336026.png)

- The MySQL Installer will install the selected products and this process may some time.After the installation is complete, click the **Next** button to proceed to the Product Configuration.

  ![image-20240821220625983](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821220625983.png)

  

##### 3. Choosing an authentication method

- In this step, configure the MySQL Server. Choose the **Development Computer** for the server configuration type, leave the other options as they are, and click the **Next** button.

  ![image-20240821220937789](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821220937789.png)

- It’s recommended to use the second option.

  ![image-20240821221204307](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821221204307.png)

- Enter a secure password for the root account.

  ![image-20240821221254336](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821221254336.png)

- Configuring MySQL Server as a Windows Service

  ![image-20240821221521152](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821221521152.png)

- In this step, you grant permission to MySQL to access the data directory.

  ![image-20240821221628483](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821221628483.png)

- click the **Next** button to confirm and finish.

  

##### **4. Complete Installation**

- After installation is complete, click the **Finish** button, and MySQL should start automatically.

- You can manage MySQL databases using MySQL Workbench or the command-line tool.

  

##### **5. Verify if the installation was successful.**

- Find the `bin` folder of the installed MySQL on your computer and get its path. The default installation path is usually: `C:\Program Files\MySQL\MySQL Server 8.0\bin`. You need to locate this path to enter the correct address in the `cmd` window.

  <img src="C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821213740065.png" alt="image-20240821213740065" style="zoom: 80%;" />

- Press Win + R, type `cmd`, and in the window that opens, enter `cd C:\Program Files\MySQL\MySQL Server 8.0\bin`.

  ![image-20240821214014687](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821214014687.png)

- Then type `mysql -h localhost -u root -p` to log in to the database, and enter the database password when prompted. Once logged in successfully, you can view the information.

  ![image-20240821214335583](C:\Users\16107\AppData\Roaming\Typora\typora-user-images\image-20240821214335583.png)

  
