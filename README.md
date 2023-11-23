# UpangLMS 

This was created by the students University of Pangasinan



# UpangLMS Virtual Host (how to run the system)
Library Management System for PHINMA - University of Pangasinan (Dagupan)
you need to follow these instructions in order to prevent broken images.
i am telling you. real talk.

Under xampp directory:

1. Go to apache/conf/extra directory
2. Open httpd-vhosts.conf with Notepad
3. Paste this at end of the file

<VirtualHost *:80>
    DocumentRoot "C:\xampp\htdocs\[folder name of your project]"
    ServerAdmin [your email address]
    ServerName  [custom url or domain you like]
</VirtualHost>

4. Replace [folder name of your project] with your project's folder
5. Replace [your email address] with your email address
6. Replace [custom url or domain you like] with the domain you like (e.g. librarymanagmentsystem.upang.local)
7. Open Notepad as an administrator (right click notepad and click run as administrator)
8. When a prompt shows up, click yes
9. Click File > Open
10. Go to C:\Windows\System32\drivers\etc
11. Select All Files in the dropdown above Open and Cancel
12. Select hosts and Open
13. Add this to the last line of the file 

127.0.0.1 [custom url or domain you like]

14. Replace [custom url or domain you like] with the domain/url from Step #6
15. Save and close notepad.
16. Stop and Start Apache in Xampp Control Panel
