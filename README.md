**********How Hackers find Location from IP Address | Cybersecurity Demo README************📒
*******************************************************************************************
📒DISCLAIMER

This project is provided "as-is" for educational purposes only.  👨‍🏫
The authors are not responsible for any damage, data loss, or legal issues that may result from using this project.

Use it responsibly and only on systems you own or have permission to test. Unauthorized use is illegal. 👮
*******************************************************************************************
YouTube Link - https://www.youtube.com/watch?v=dmpEckWOAXc 🌐

1. Clone the repository here - https://github.com/rajkumardusad/IP-Tracer. 🌐
2. <Copy & Paste>: git clone https://github.com/rajkumardusad/IP-Tracer.git at the Kali Linux prompt.
3. <Copy & Paste>: cd IP-Tracer - [to change to the IP-Tracer directory].
4. Type #ls to see the main script file - [ip-tracer].
5. <Copy & Paste>: chmod +x install.
6. <Copy & Paste>: sh install or ./install.
7. Launch the tool by typing IP-tracer.
8. Type - trace -t < IP address>.
9. Seconds later, information is displayed about the IP address.
**************************************************************
🚀How to install IP-Tracer?:

apt update
apt install git -y🛠️
git clone https://github.com/rajkumardusad/IP-Tracer.git
cd IP-Tracer
chmod +x install
sh install or ./install

📒How to use IP-Tracer:

trace -m to track your own ip address. 🔎
trace -t target-ip to track other's ip address for example ip-tracer -t 127.0.0.1
trace for more information.

📒OR:

ip-tracer -m to track your own ip address.
ip-tracer -t target-ip to track other's ip address for example ip-tracer -t 127.0.0.1
ip-tracer for more information.
*********************************************
└─$ ip-tracer
Usage: trace [command]... [arguments]...
 Commands:
 -t <target_ip>      to trace target ip.
 -m                  to trace your own ip.
 -h                  to show help.
 -u                  to update ip-tracer.
 help                to show help.
 update              to update ip-tracer.
 start               to start ip-tracer menu.
┌──(kali㉿kali)-[~]
└─$ ip-tracer start - to open the IP tracer tool!
