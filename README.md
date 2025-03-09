# Password Vault Practices 


This guide outlines a flexible workflow for managing your passwords using open-source tools, ensuring that your sensitive information isn't confined to a single company's ecosystem.


## Step 1: Generate an Encrypted Database with KeePass 

Begin by using [KeePass](https://keepass.info/) , an open-source password manager, to create an AES-256 encrypted database file. This file will securely store all your passwords and related information.

## Step 2: Store the Database in a Cloud Service 


Place your KeePass database file in a cloud storage service like OneDrive, which offers 5GB of free storage. This setup allows you to access your password database from multiple devices.


## Step 3: Access Your Passwords on Different Platforms 


### Desktop Access with KeeWeb 

[KeeWeb](https://keeweb.info/)  is an open-source desktop application that integrates seamlessly with cloud services:
 
- **One-Time Setup** : Log in to your OneDrive account through KeeWeb and link it to your KeePass database file.
 
- **Secure Access** : Each time you open KeeWeb, you'll be prompted to enter your database password, ensuring secure access to your credentials.


### Mobile Access with StrongBox (iOS) 

For iOS users, [StrongBox](https://strongboxsafe.com/)  offers a polished experience:
 
- **Initial Setup** : Link StrongBox to your OneDrive account and point it to your KeePass database file.
 
- **Features** : Enjoy password autofill, Face ID or Touch ID authentication, and a user-friendly interface.
 
- **Pricing** : Free for the first 90 days, with a one-time purchase option for lifetime access.


## Benefits of This Approach 

 
- **Control Over Your Data** : You decide where your encrypted database resides, whether it's OneDrive, Google Drive, Dropbox, or even a personal FTP server. This flexibility means you're not locked into a single service provider.
 
- **Enhanced Security** : Cloud storage services only hold your encrypted database file. Without your master password, accessing the contents is virtually impossible.
 
- **Rich Features** : KeeWeb offers functionalities like:

  - Organizing entries into folders (e.g., personal, work, family).

  - Storing images and attachments, such as PDFs or photos of credit cards.

  - Creating custom fields for specific account details.

  - Autofilling credentials directly from the app.


By adopting this workflow, you maintain full control over your sensitive data, leveraging open-source tools and flexible storage options to manage your passwords securely and efficiently.
