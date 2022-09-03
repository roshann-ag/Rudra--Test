# Rudra--Test
Git Commands to get started with:

┌──(kaliuser㉿kali)-[~/Documents]
└─$ git config --global user.name "Roshann Agarwal" 
┌──(kaliuser㉿kali)-[~/Documents]
└─$ git config --global user.email "r.agarwal@outlook.in" 
┌──(kaliuser㉿kali)-[~/Documents]
└─$ git config --list
user.name=Roshann Agarwal
user.email=r.agarwal@outlook.in 
┌──(kaliuser㉿kali)-[~/Documents]
└─$ git init Rudra--Test
Initialized empty Git repository in /home/kaliuser/Documents/Rudra--Test/.git/ 
┌──(kaliuser㉿kali)-[~/Documents]
└─$ echo "# Rudra--Test" >> Rudra--Test/Readme.md
┌──(kaliuser㉿kali)-[~/Documents]
└─$ cd Rudra--Test/ 
┌──(kaliuser㉿kali)-[~/Documents/Rudra--Test]
└─$ git status
On branch master
No commits yet
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	Readme.md
nothing added to commit but untracked files present (use "git add" to track)
┌──(kaliuser㉿kali)-[~/Documents/Rudra--Test]
└─$ git add . 
┌──(kaliuser㉿kali)-[~/Documents/Rudra--Test]
└─$ git status
On branch master
No commits yet
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   Readme.md                                                                                
┌──(kaliuser㉿kali)-[~/Documents/Rudra--Test]
└─$ git commit -m "first commit"
[master (root-commit) 6105c79] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 Readme.md                                                                                
┌──(kaliuser㉿kali)-[~/Documents/Rudra--Test]
└─$ git branch -M main 
┌──(kaliuser㉿kali)-[~/Documents/Rudra--Test]
└─$ git remote add origin https://github.com/roshann-ag/Rudra--Test.git 
┌──(kaliuser㉿kali)-[~/Documents/Rudra--Test]
└─$ git push -u origin main
Username for 'https://github.com': roshann-ag
Password for 'https://roshann-ag@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 229 bytes | 229.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/roshann-ag/Rudra--Test.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
