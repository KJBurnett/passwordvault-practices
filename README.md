# Password Vault Practices
a readme describing my workflow for a flexible password vault that isn't constrained to a single company's ownership.

So, there's an open source program called keepass2
https://keepass.info/

You only need to use it once to generate an AES-256+ encrypted database file.

Then what I did was I stuck it in my onedrive folder. Which onedrive is 100% free for like 5GB or something. 

Then, there's a 100% open source app on github called keeweb. It's a downloadable and installable desktop app.
https://keeweb.info/ You login to your onedrive through the app a single time. And it links to your database file you created. Then whenever you open the keeweb app, it makes you type in your database file's password.

On iOS, there's an extremely polished app written by one of the same developers who worked on keeweb called StrongBox. It's free for 90 whole days, and then like $10 for the full app for life. And you just do a one-time link up to your onedrive, point it to the database file, and boom you're done. I love strongbox because it has password auto fill on your phone, and it works with face id or touch id or a pin.

The best part about doing it this method is /you/ are in control of where your database file with all of your passwords, account information, etc live.
If you suddenly hate onedrive one day. NBD, move it to another storage service you trust more. (google drive, dropbox, {insert-storage-company-name-here}, heck, you can even put the databse file on your computer and link it to your devices via an FTP filezilla server (not recommend because if your internet or power goes out you lose connection to your computer lol)
The point is, you kinda permanently control where your really important and private data is instead of trusting a service like microsoft authenticator, or lastpass, or finalpass, or keyvault, etc
Even microsoft onedrive doesn't have actual access to your passwords because all it's doing is storing the encrypted database file. They would have to know the password to the database file to open it. Which is only entered through the tunnel from keeweb or strongbox
Plus, keeweb has a TON of features

you can create folders, example I have a folder for personal, work, and for family because my parents always forget their passwords
you can store images, attachments like pdfs, and even pictures of your credit cards or something. You can create a customized field for any account. example if I wanna access my becu, I just open keeweb, type in my master password, search becu, click the becu link and it will auto fill the password and account because I did it from the password vault app
