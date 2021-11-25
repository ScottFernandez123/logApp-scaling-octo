 # README

 > **NAME**

Using MySQL Workbench to Execute SQL Queries and Create SQL Scripts

 > **DESCRIPTION**


Before any SQL statements can be executed on a database, the MySQL Workbench tool must first establish a connection to the target database server. This may take the form of a local server that is running on the same host as the workbench, or a server running on a remote system. To establish such a connection, begin by launching the workbench tool. Once running, the home screen should appear as shown in the following figure:

If the required connection is already listed in the SQL Development column of the workbench home page, simply double click on it to establish the connection and enter the corresponding password. Alternatively, click on New Connection to display the new connection dialog:

[Reference](https://www.techotopia.com/index.php?title=Using_MySQL_Workbench_to_Execute_SQL_Queries_and_Create_SQL_Scripts&mobileaction=toggle_view_mobile)

  > **VISUAL**

![SQL Development column](https://www.techotopia.com/images/0/0d/Mysql_workbench_home_screen_no_connection.jpg)

![TCP/IP](https://www.techotopia.com/images/d/d9/Mysql_workbench_setup_connection.jpg?ezimgfmt=rs:807x535/rscb1/ng:webp/ngcb1)

![Connect Server](https://www.techotopia.com/images/f/fd/Mysql_workbench_sql_dev_connection.jpg?ezimgfmt=rs:319x400/rscb1/ng:webp/ngcb1)


  > **INSTALLATION**

  Here are the steps for installation using MySQL Installer
  
  1. First thing to do is to download and install the MySQL Installer.

  2. During execution of the MySQL Installer you may choose MySQL workbench as one of the products to install. It is selected by default, and essentially executes the standalone MSI Installer package described in the next section.

> **Installation Using the Windows MSI Installer Package**


The standalone download is available here It is important to note that Workbench using Windows MSI Installer package requires either Administrator or Power user privileges.
MySQL Workbench can be installed using the Windows MSI Installer package. The MSI package bears the name mysql-workbench-community-version-winarch.msi, where version indicates the MySQL Workbench version number, and arch the build architecture (winx64).
To install work using this approach follow the steps below.
From an account with Administrator or Power User privileges, right-click the MSI file and select the Install item from the pop-up menu, or double-click the file.
In the Setup Type window you may choose a Complete or Custom installation. To use all features of MySQL Workbench choose the Complete option.
Unless you choose otherwise, MySQL Workbench is installed in C:\%PROGRAMFILES%\MySQL\MySQL Workbench 8.0 edition_type\, where %PROGRAMFILES% is the default directory for programs for your locale. The %PROGRAMFILES% directory is defined as C:\Program Files\ on most systems.




> **AUTHOR**

> Author Name: Froyland Scott, Fernandez


![DATABASE](https://scontent.fmnl13-1.fna.fbcdn.net/v/t39.30808-6/249285191_7179366005422700_8289433521635325324_n.jpg?_nc_cat=102&ccb=1-5&_nc_sid=09cbfe&_nc_eui2=AeGb2qtpDCssEyotU3i36HxZd1btjvLMZ_t3Vu2O8sxn-xASmLpPLnHLf6QwSlw47S1nLUCC6tWaIP4sYYIoJcAk&_nc_ohc=1sGD5n1wP0sAX9pxyMN&_nc_ht=scontent.fmnl13-1.fna&oh=f4912975ff4c508740c50bc220e5d6db&oe=61A521AC)

|  **References**                                     |
| ------------------------------------------------------------ |
| [How to Install MySQL]
