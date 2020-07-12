# Bank_management
> An mini project for C language demonstrating the bank management system.
   I made it using C in JAN 2018 for PCI (Programming In C language(22226)) at Amrutvahini Polytechnic.

> __This project relies on File handling for its functionality. Does not impelements Database__


#### This Mini project implements
* Admin Login
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
