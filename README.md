Active Directory Creation and Securing ADFS/LDAP 
 
* Tools and OS required:
    * Windows Server 2019 (Domain controller)
    * Windows 10 Enterprise — User-machine 1
    * Windows 10 Enterprise — User-machine 2

* Process:
    *  We need to install Windows Server 2019 Eval Center in Virtualbox -> Setting up Domain Controller -> Adding Roles -> Active Directory Domain Services role -> Add a new forest-> setting a password for DSRM (Directory Services Restore Mode) -> Keep Windows 2019 Server details such as Administrator username and password used during forest creation
    * Create 2 user machines by installing Windows 10 enterprise eval iso through virtual box -> add both to the domain created as per Windows Server 2019 
    * Active Directory (AD) Setup, Groups, and Policies: Log in to the Windows Server-> New" > "Organizational Unit from AD within the windows server
    * Move all users (except Administrator and Guest) from the “Users” directory to the “Groups” directory.
    * Create users with username and password 
    * Login to both user machines ie Windows 10 with new username and password.
    * Now try changing password through AD within Windows 2019 and implement lab solution on user machines
    * Also try changing group policies within AD for users to grant admin access to install stuff in windows 10 systems .
