# Linux
<h1> Basic linux command</h1>

pwd	-------- Show current directory (Print Working Directory).
ls	-------- List files and directories in the current location.
ls  --------- -l	Show detailed list (permissions, owner, size, date).
ls  --------- -a	Show hidden files.
cd  --------- directory_name	Change directory.
cd .. --------	Move up one directory level.
mkdir ------- new_folder	Create a new directory.
rmdir folder_name -------- 	Delete an empty directory.
rm file_name -------	Delete a file.
rm -r folder_name --------	Delete a directory with all its contents.
touch -----  file_name	Create an empty file.
cp --------- source destination	Copy a file.
cp -r source destination	-------- Copy a directory.
mv old_name new_name --------- 	Rename or move a file.


<h2>  File Viewing Commands</h2>


cat file_name -------- Show file contents.
less file_name ---------	View file contents page by page.
head file_name --------	Show first 10 lines of a file.
tail file_name -------	Show last 10 lines of a file.
tail -f file_name -------	Continuously monitor file changes (useful for logs).


<h3> Permissions and Ownership</h3>

ls -l	------------ Show file permissions.
chmod 777 file_name -------	Change file permissions (777 = full access).
chown user:group file_name -------	Change file ownership.

<h4>  Process Management </h4>

ps	--------- Show running processes.
top	------- Display real-time system usage.
kill PID -------	Kill a process by its Process ID (PID).
kill -9 ------ PID	Force kill a process.


<h5> Networking Commands </h5>

ping google.com	------ Check network connectivity.
curl url -------	Fetch data from a URL.
wget url	-------- Download a file from a URL.

