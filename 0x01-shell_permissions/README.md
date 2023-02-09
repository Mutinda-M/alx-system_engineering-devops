su betty changes user to betty
whoami prints effective username of current user
sudo chown betty hello changes ownership of file hello to user betty
touch hello  creates an empty file named hello
chmod u+x ./hello adds execute permission to hello file at cd
chmod 754 ./hello add execute to user and group ,adds write to others
chmod a+x ./hello adds execution to all
chmod 007 ./hello gives permission to others only
chmod 753 ./hello -rwxr-w-wx
chmod --reference=./olleh /.hello change mode of hello to be exact as that of olleh
chmod a+x . add execution permission to all subdirectories in working directory
mkdir -m 751 ./my_dir creates directory my_dir in current working folder with 751 permissions
sudo chgrp school ./hello changes group owner to school
