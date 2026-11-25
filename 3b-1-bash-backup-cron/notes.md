Reflection questions and my answers 

Q1 Why is using absolute pats important in scripts run by cron? 

So Cron doesn't run my script from the folder i happen to be in. It starts the job from the jome folder of whichever user it runs as, and with a minimal environment
that doesn't load my .bashrc. So a short path like Documents/* or ~/backup could point somewhere unexpected. The lab's example ran as root, where ~ means /root, not /home/ubuntu.
I used full paths like /home/zach/Documents and /home/zach/key.pem everywhere, so the script finds the same files no matter who runs it or from where. I saw how easily paths go wrong in the permissions lab,
when typing home/shared without the leading / made Linux look in the wrong place.


Q2 What are the benefits of cloud exporting for backups? 

the benefits are that sending a copy to a separate server means that any failure like disk failure or a machine being hit by ransomware. cant take out both copies at the same time 
in my lab i used a secondary VM to stand in for a cloud server and i copied each zip over with scp but a real cloud server would add more protection against a whole site going down, such as fires or power going out 
because the copy sits in a different location.


Q3 How does cron differ from manual execution? 

