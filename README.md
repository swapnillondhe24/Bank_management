# Bank_management
> An mini project for C language demonstrating the bank management system.
   I made it using C in JAN 2018 for PCI (Programming In C language(22226)) at Amrutvahini Polytechnic.

> __This project relies on File handling for its functionality. Does not impelements Database__


#### This Mini project implements
* Admin Login
   
   `Admin username : ` __ADMIN__
   
   `Admin Password : ` __MICROPRJCT__
  * Create User
  * Delete User
  * View User Log
  
* Staff Login

  * Create New Acccount
  * Cash Deposit
  * Cash Withdrawl
  * Fund Transfer
  * Account Information
  * Transcation Information
  
* Staff login users

   | USER ID 	| USERNAME 	| PASSWORD 	|
   |-----	|---------	|-------------	|
   | U01 	| SWAPNIL 	| !SWAPNIL123 	|
   | U02 	| DOMNIC  	| !DOMNIC123  	|
   | U03 	| JADEN   	| !JADEN123   	|
   | U04 	| JOHN    	| !JOHN123    	|
   | U06 	| WILL    	| !WILL123    	|
   | U08 	| SHIVA   	| !SHIVA123   	|
   
### Instructions to Run this Code:
* #### For Linux Users
    ```bash
     git clone https://github.com/swapnillondhe24/Bank_management 
     cd Bank_management
     gcc bnkmgt.c
     ./a.out
     ```
> _have not tested this code to run on Linux system may need changes_

* #### For Windows Users
    ```bash
     git clone https://github.com/swapnillondhe24/Bank_management 
     cd Bank_management
     ```
> _This project was entirely build using **[Dev-C++](https://bloodshed-dev-c.en.softonic.com/download)** IDE_


### Details of Files included
* __bnkmgt.c__
   > This includes all the C Code.
* __LOG.DAT__ 
   > This DAT file is used to Store all the logs data which includes _Account opening_ ,_Account closing_ , _Modifications in Account_ , _Fund Transfer_, _etc._  and is accessed in the Staff login
* __TRANSACTION.DAT__
   > This DAT file is used to Store all the transactional logs and is accessed in the Staff login
* __ACCOUNT.DAT__
   > This DAT file is used to Store all the Account Details. _Account created by staff members_ logs and is accessed in the Staff login
* __USER.DAT__
   > This DAT file contains _User ID_ , _Username_ , _Password_ of all the user created by admin. these details are of staff login.
    
## RESULTS.
**welcome screen one**

![Image of Welcome screen one](https://github.com/swapnillondhe24/Bank_management/blob/master/Images/wel1.png)

**welcome screen two**

![Image of Welcome screen two](https://github.com/swapnillondhe24/Bank_management/blob/master/Images/wel2.png)

**Admin of staff login selection**

![Image of Login Type Selector](https://github.com/swapnillondhe24/Bank_management/blob/master/Images/admin_or_staff.png)

**Admin Panel**

![Image of Admin Panel](https://github.com/swapnillondhe24/Bank_management/blob/master/Images/admin_panel.png)

**Staff User Creation**

![Image of Staff user creation](https://github.com/swapnillondhe24/Bank_management/blob/master/Images/Staff_user_creation.png)

**Staff Panel**

![Image of Staff Panel](https://github.com/swapnillondhe24/Bank_management/blob/master/Images/Staff_panel.png)

**Account Information**

![Image of Account information](https://github.com/swapnillondhe24/Bank_management/blob/master/Images/account_information.png)
