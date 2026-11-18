# Git
AIM: Basic Commands
Step 1: git config --global user.name “anjalibansode-17”
Step 2: git config --global user.email
“bansode.anjali1703@gmail.com ”
Step 3: git init
Step 4: cd desktop
Step 5: mkdir 007_anjali
Step 6: cd 007_anjali
Step 7: nano app.py
Step 8: git init
Step 9: git add .
Step10: git commit -m ”new mess”
Step 11: git remote add origin
“https://github.com/anjalibansode-17/007_anjali.git”
Step 12: git push -u origin master 



AIM: Basic Commands
Step 1: git checkout -b login
Step 2: git pull origin master
Step 3: nano login.py
Step 4:git status
Step 5: git add login.py
Step 6: git status
Step 7: git commit -m "Added a mess"
Step 8: git status
Step 9: git checkout master
Step 10: git merge login
￼
Step 11: git status
Step 12: git push origin master
Step 13: Authenticate and then again run step 12 







AIM: To install and configure Jenkins on a local system and create
an automated CI/CD pipeline that integrates with a version
control system, enabling continuous integration and continuous
deployment of a sample application.
IN VMWare (Windows)
Install Git, Java 25, Jenkins in VMWare(Windows)
For jenkins:
Paste the localhost:8080 in url line, red line copy paste in in FE
home>path, open notepad, paste the password in url, download
suggest plugins, create acc username:anjali password:anjali007







Create new pipline-git-add ur file- convert slashes and add file:///
-create pipeline

Go to tools-Program files-git-bin- copy that path paste+
\git.exe-clone the repository-copy the path of the repository file-
paste it after file:///-change all the slashes- name the conflict.



Click + name it-add step-window batch script-in script put echo
“name”-save-sun n run





PRACTICAL 4
AIM: Docker
Refer this:
https://chatgpt.com/share/6abb9a16-7440-83e8-9db2-7933ce8
445cf
In CMD, Run these:
1. .\bcdedit.exe /set hypervisorlaunchtype off
2. .\reg.exe add
"HKLM\SYSTEM\CurrentControlSet\Control\DeviceGuard"
/v EnableVirtualizationBasedSecurity /t REG_DWORD /d 0
/f
3. .\reg.exe add
"HKLM\SYSTEM\CurrentControlSet\Control\DeviceGuard\
Scenarios\HypervisorEnforcedCodeIntegrity" /v Enabled /t
REG_DWORD /d 0 /f
Restart the system
Windows security-device security- core isolation- memory
integrity off

In VMWare setting change number of processors to 4, restart the
vm
￼

In both, local n vm, run these commands:
1. dism.exe /online /enable-feature
/featurename:Microsoft-Windows-Subsystem-Linux /all
/norestart
2. dism.exe /online /enable-feature
/featurename:VirtualMachinePlatform /all /norestart

Powershell run as administrator: docker run hello-world

set up ends 


Create a website and put it on github
In bash





