Step1: Have to create a new repository in your github profile.

Step2: Then copy the repository link from online and clone to your desktop by your gitbash command promot following this command.
	$git clone paste_the_Link

Step3: Have to insert into the cloned folder/directory by following this command
	$cd FolderName/DirectoryName

Step4: To create any file
	$touch FileName.withExtension

Step5: For the file into vscode editor
	$code .
	or 
	$code FileName.withExtension

Step6: Then you can write code into your file.

Step7: After writing code you can check your git status by this command. And you show redmark file. Because you do not stage your file yet into git.
	$git status

Step8: This time for staging. You have to add this file for staging by this command.
	$git add .(dot for all file)
	or
	$git add FileName.withExtension(for single file staging)

Step9: After staging you have to check your status by the status command and show greenmark file. It's means your file added.

Step10: Now you have to commit your file with message by this command.
	$git commit -m "Your message."

Step11: Now you have to push your file in online by this command
	$git push origin master --force
	give the github username:
	give the github password:

done