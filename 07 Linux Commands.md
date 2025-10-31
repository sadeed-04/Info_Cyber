# Linux command
# 1)Package Management (Debian-example)
| Command | Description | Example |
|---------|-------------|---------|
| 'apt update'| update repo  info | 'sudo apt update ' |
| 'apt upgrade' | upgrade package | 'sudo apt upgrade' |
| 'apt install' | Install a package | 'sudo apt install nmap'|
| 'apt remove' | Remove a packge | 'sudo apt Remove apachez'|

# 2) file & directory command
| command | description | example |
|---------|-------------|---------|
| 'pwd' | show current directory | 'pwd'|
| 'ls' | List files/directories | 'ls' |
| 'ls -l' | Detailed Listing | 'ls -l' |
| 'ls -a ' | Show Hidden Files | 'ls -a' |
| 'cd' | Change Directory | 'cd/etc'|
| 'cd ..' | Go up one level | 'cd ..' |
| 'cd ~' | Go to home directory | 'cd ~'|
| 'mkdir' | create directory | 'mkdir testdir' |
| 'rmdir' | Remove empty directory | 'rmdir testdir' |
| 'rm' | remove Files/directories | 'rm file.txt','rm -r dir/'|
| 'touch' | Create empty files | 'touch file1.txt' |
| 'cp' | Copy file/directory | 'cp file1.txt file2.txt' |
| 'mv' | Move/Rename file | 'mv file1.txt file1.txt' |
| 'find' | search for files | 'file . -name "*.sh"'|

# 3) File Content Commands
| Command    | Description  | Example |
|-----------|---------------|---------|
| 'cat'     | View file content | 'cat file.txt' |
| 'more','less' | View file with scroll | 'less file.txt' |
| 'head' | View first 10 lines    | 'head file.txt' |
| 'tail' | View last 10 lines   | 'tail file.txt' |
| 'wc' | word/line count | 'wc -l file.txt' |
| 'cut' | Extract columns | 'cut-d','-f1 file.csv' |
| 'sort' | Sort file lines | 'sort file.txt' |
| 'uniq' | Remove duplicate | 'uniq file.txt' |
| 'diff' | show difference between files | 'diff file1 file2' |

# 4) User & Permissions
| command | description | Example |
|-------------------|---------------------|--------------|
| 'whoami' | Show current user | 'whoami' |
| 'id' | show user/group IDs | 'id' |
| 'chmod' | change permissions | 'chmod 755 script.sh' |
| 'chown' | change owner | "chown root:root file.txt |
| 'adduser' | Add user | 'adduser alice' |
| 'passwd' | Change password | 'passwd alice' |
| 'su' | switch user | 'su -' |
| 'sudo' | Run as superuser | 'sudo apt update' |


# 5) Networking 
| Command             | Description             | Example                         |
|---------------------|-------------------------|---------------------------------|
| ' ping '            | Test connectivity       | 'ping google.com'               |
| 'ifconfig' / 'ip a' | view network interfaces | 'ip a'                          |
| ' netstat -tuln'    | View open ports         | 'netstat -tuln'                 |
| 'curl'              | Fetch URLs              | 'curl http://example.com'       |
| 'wget'              | Download files          | 'wget http://file.com/file.txt' |

# 6) File compression & Archiving
| Command     | Description         | Example                          |
|-------------|---------------------|----------------------------------|
| 'tar'       | Archive files       | tar -cvf archive.tar file1 file2 |
| 'tar -xvf'  | Extract tar archive | tar -xvf archive.tar             |
| 'tar -czvf' | Create gzip tar     | tar -czvf archive.tar.gz dir/    |
| 'gzip'      | Compress file       | gzip file.txt                    |
| 'gunzip'    | Decompress '.gz'    | gunzip file.txt.gz               |
| 'zip'       | Zip files           | zip archive.zip file1 file2      |
| 'unzip'     | Unzip archives      | unzip archive.zip                |
