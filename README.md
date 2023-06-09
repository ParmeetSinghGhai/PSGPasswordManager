# PSGDriveSync Application
This application allows users to 
- Create secure passwords upto 2000 characters long for one time use where you get full control over the password generation process.
- Create secure passwords upto 2000 characters long and have them added to local files called 'vaults' which are themselves encrypted with AES-256 encryption standard using a master password. 

## Prerequisite
- Currently the application is only supported on Windows Operation System.
- Its has been developed using .Net Framework 4.8 hence .Net Framework Runtime Environment is required to run the application. It can be downloaded from [Microsoft](https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-web-installer)

## Features Of the Application
![PasswordGeneratorTab](https://parmeetsinghghai.github.io/psgpasswordmanager/assets/img/password.png)
### Strong Passwords
Generate Strong Password of Upto 2000 Characters Long where you get Full Control over how many Lower Case Characters, Upper Case Characters, Special Symbols and Numbers will be present in those Password(s).

![PasswordGeneratorTab](https://parmeetsinghghai.github.io/psgpasswordmanager/assets/img/encryption.png)
### AES-256 Encryption Based 'Vaults'
Save above password(s) or any other data like bank account numbers, social security number etc in local files called 'vaults'. these 'vaults' are encrypted with AES-256 encryption standard using a master key that only you know. the master key for each 'vault' is not saved anywhere so please make sure that you remember the master password for these 'vaults'.

### Long and Random Files Names For 'Vault" Files 
every 'vault' file is given a long (128 characters long) file name made up of random characters and numbers. This allows you to identify which vault file is which only by 'unlocking' or opening a 'vault' using its master password and seeing its tag using the application. 

![PasswordGeneratorTab](https://parmeetsinghghai.github.io/psgpasswordmanager/assets/img/protected.png)
### Hidden and System Protected 'Vault' Files
all 'vault' files generated by the application are hidden and system protected and if any one of these attributes is changed then the application will stop processing those vault files as a security measure.

![PasswordGeneratorTab](https://parmeetsinghghai.github.io/psgpasswordmanager/assets/img/vaultmanagement.png)
### Vault Management
- you can add as many vaults as you like
- you can open multiple vaults from one folder or directory using one master key
- you can update multiple vaults at the same time changing their master password, tag, or data
- you can delete vaults anytime as well 
- search for multiple vaults in one folder or directory

![PasswordGeneratorTab](https://parmeetsinghghai.github.io/psgpasswordmanager/assets/img/camouflage.png)
### Camouflage Vault Files
The 'Camouflage Vault' feature under Vault Management tabs allows you to create upto 100 random vaults at a time in the same folder or directory as your own vault.The purpose of doing this is to make things difficult for the person who has access to your vault files and is trying to decrypt or unlock your vault's content without knowing its master password.

In such a hypothetical situation, this person would have to first guess which is the correct vault file that they need to work with, since all of them have 128 characters long file name which contain random letters and number, and then they would have to guess the master password to get the content of the vault file. 

### Send To Clipboard and Clear Clipboard
send secure password or data inside a 'vault' to clipboard with the click of a button. You can also clear the clipboard content anytime by pressing the 'clear clipboard' button.

![PasswordGeneratorTab](https://parmeetsinghghai.github.io/psgpasswordmanager/assets/img/autotype.png)
### Send To Window
some websites do not allow users to copy and paste passwords instead they force users to type their password using their keyboard. if your secure password is 2000 characters long with random characters, symbols and numbers then it would be real difficult to type all those keys in with a keyboard. The solution here is the "Send To Window" button. Simply click on the button and then click on any other window of your choosing like firefox web browser, internet explorer, notepad, word etc using the mouse left click and after that press the "command key" which by default is set to "LEft Shift" key on the keyboard. This application will then take over and type those long secure passwords for you in the selected window. You can abort this functionality by clicking on the button again but only when it has not started typing.

** Please note: a 2000 characters long password can take up to 1.39 minutes to type completely **

### Change "Command Key" for Above Functionality Anytime
you can change the "command key" for the above "send to window" functionality anytime by clicking on the "command key" button and pressing a key of your choice on the keyboard. To abort simply click on the button again. Please use a non-printing key like Ctrl, Shift, Alt, F1, F2 etc 

### Simple To Use Graphical User Interface

## Installation Instructions
- Download the file "PSGPasswordManager.zip".
- Unzip its contents to any folder of your choosing. 
- Run application "PSGPasswordManager.exe"

## License 
The application can be used free of charge but only for personal use.

## User Guide
The application has two main tabs namely: Password Generator and Vault Management

![PasswordGeneratorTab](https://parmeetsinghghai.github.io/psgpasswordmanager/assets/img/tab1.png)

### Password Generator Tab
this tab allows you to set the settings for the number of lowercase characters, uppercase characters , symbols and numbers to be present in your random and secure passwords and you also set the overall length of the passwords as well. 


for example: if a password of 400 characters long with 100 lower case characters, 100 uppercase characters, 100 symbols and 100 numbers is needed then the
- 'Password Length' can be set to 400
- 'LowerCase Characters' should be set to 25%
- 'UpperCase Characters' should be set to 25%
- 'Symbols' should be set to 25%
- 'Numbers' should be set to 25%

Please the order of precendence of one setting over the other is from top to bottom where if lower case characters are set to 100 and all other settings are also set to 100 then the generated password will only contain lower case characters. 

![PasswordGeneratorTab](https://parmeetsinghghai.github.io/psgpasswordmanager/assets/img/tab2.png)
### Vault Management Tab
a) Search Path: you need to type in the path of the vault file or the path of the folder that contains vault file(s). you can use the "Browse For Folder" to pick a folder in a folder dialog box. After that you can click on "Seach Path" and that will display all the vault files present in the path that you entered. 

b) Add Vault Form: to create a new vault file use this feature. you need to provide the following info to make this work:
  - path of the folder which will contain this newly generated vault file
  - a tag or name attached to your vault that will help you recognize this vault. 
  - master password for the vault which will be used to open this vault later on.
  - vault data which can be any text of your choosing or if you would like you can check "auto generate vault data" to allow the application to create a random password using the settings in "password generator" tab and then put that password in the vault.
 
c) Open Vault Form: after you have used the search path functionality to display all the vaults in a particular location, you can go ahead and click on 
'open vault form' to get those vaults open. First you need to select the vaults which you would like to open and then enter the common master password for those vault(s). After that click on the "Open Vault(s) button to get those vaults opened up.

d) Update Vault Form: its used to change the master password, tag and data of an vault. you can choose to skip the master password and tag , if needed and only update a vault's data. 

e) Camouflage Vault Form: it allows you to create random vaults in the same location as your vault using random tags, password and data thus sort of camouflaging your vault in the process. specify the number of these random vaults that you would like the application to create and then click on "Camouflage Vault(s).  

![PasswordGeneratorTab](https://parmeetsinghghai.github.io/psgpasswordmanager/assets/img/tab3.png)
### Support Functionalities
a) Register Command Key: the default command key set for "send to window" functionality is set to "Left Shift Key" but you can change it anytime by clicking on this button and then pressing a key on the keyboard of your choosing. if you would like to stop this process then you can go ahead and click on this button again

b) Send To Window: this functionality allows the application to type in the vault data or a password generated in "password generator" tab in any window of your choosing. Simply click on a window first to make it show on your desktop and then press the set command key in that window to make the application start typing in your password for you. This functionality would be real helpful for websites like a bank website which does not allow you to copy and paste your password. 

c) Send To Clipboard: this functionality allows the application to copy your password or vault data in windows clipboard which you can then use to paste this data in any other window that allows cut-copy-paste functionality

d) Clear Clipboard: this functionality allows you to clear the clipboard content. 

## Terms & Conditions
This EULA sets out the basis on which Parmeet Singh Ghai (the "Vendor") makes the Products available to you (“User” or ”You”) and on which You may use them. By installing or using the Product, You agree to accept and to be bound by this EULA. If You do not agree with one of these, please do not install or use the Product.

1.0 The Software is provided by the Vendor and accepted by the Licensee "as is". Liability of the Vendor will be limited to a maximum of the original purchase price of the Software. The Vendor will not be liable for any general, special, incidental or consequential damages including, but not limited to, loss of production, loss of profits, loss of revenue, loss of data, or any other business or economic disadvantage suffered by the Licensee arising out of the use or failure to use the Software.

1.1 The Vendor makes no warranty expressed or implied regarding the fitness of the Software for a particular purpose or that the Software will be suitable or appropriate for the specific requirements of the Licensee.

1.2 The Vendor does not warrant that use of the Software will be uninterrupted or error-free. The Licensee accepts that software in general is prone to bugs and flaws within an acceptable level as determined in the industry.

1.3 The Vendor works hard to ensure that the Software does not contain any “back door,” “time bomb,” “Trojan horse,” “worm,” “drop dead device,” “virus”, “preventative routines,” “disabling code,” “cookie” or other computer software routines or programming devices designed to (i) permit unauthorized persons to access the Software, (ii) intentionally disable, modify, destroy or damage the Software, and/or (iii) make the Software inaccessible or delayed.

## Privacy Policy
No data is collected during the use of this application. its a local desktop application. 

## Contact Information 
You can contact me @
- parmeet.s.ghai@gmail.com 
- parmeet.s.ghai.businesssolutions@gmail.com

