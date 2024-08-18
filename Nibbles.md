











For uploading a reverse shell, one line php rev shell command did not work from pentestmonkey. Therefore I used the HTB Module one. After getting Reverse shell, and taking the user flag, I looked for Privelege escalation. Exploring, found monitor.sh has access without sudo passwd. echoing "bash -i" > and sudo running, we got escalated and caught the root flag



![image](https://github.com/user-attachments/assets/d0391367-937b-402d-b6aa-c68ea9fdf612)
