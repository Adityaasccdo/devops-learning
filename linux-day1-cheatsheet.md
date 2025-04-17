🧾 Linux Day 1 Cheat Sheet – DevOps Starter

🔧 Directory & File Navigation

Command	        Meaning	                Description
pwd     	Print Working Directory	Shows the current folder path
ls      	List	                Lists all files and folders in the current directory
ls -l   	Long Listing	        Shows detailed file/folder info (permissions, size, date)
cd foldername/	Change Directory	Moves into a folder
cd ..   	Parent Directory	Go up one folder level
cd ../../	Go up 2 levels	        Moves two folders back
cd ~    	Home directory  	Goes to your user home directory
cd -    	Go back         	Switches to the previous directory


📂 Creating Files & Folders

Command			Meaning			Description
mkdir foldername	Make Directory		Creates a new folder
touch filename		Touch (new file)	Creates a new empty file
echo "text" > file.txt	Write to file		Overwrites file with new content
echo "text" >> file.txt	Append			Adds text to end of file without overwriting
cat filename		Concatenate			Displays content of a file


🚚 Moving, Copying & Deleting
Command			Meaning		Description
cp source.txt dest/	Copy			Copies file into destination folder
mv file.txt newfolder/	Move			Moves file into another folder
rm filename		Remove			Deletes a file
rm -r foldername	Recursive Remove	Deletes a folder and everything inside it


🔐 Permissions & Ownership
Command			Meaning		Description
chmod +x script.sh	Change Mode	Makes a file executable
sudo			Superuser Do	Runs command with root (admin) privileges
chown user:group file	Change Owner	Changes ownership of a file

📜 Running Scripts   
Command				Description
#!/bin/bash			Shebang – tells system to use bash
nano file.sh / vim file.sh	Open file in editor
./script.sh			Run script from current directory
`echo "..."	sudo tee file.sh`

👥 User & Info Commands
Command		Description
whoami		Shows current logged-in user
date		Shows current date and time
history		Shows command history
