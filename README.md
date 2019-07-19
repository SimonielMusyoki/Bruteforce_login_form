# Bruteforce_login_form

This is a scapy code for detecting if your ARP has been spoofed by an  attack

Requires:<br>
<ul>
<li>Python3</li>
<li>Super user priviledges but not a must</li>
<li>requests library installed: ~~pip install requests~~ if you dont have it</li>
</ul>

Usage:<br>
 change the target_url variable to the exact login url for the target web.<br>
 Add a password_list.txt in the same directory with the python file. This file should contain all the passwords you would like to try <br>
 Change the username value in the data_dict dictionary to the intended username<br>
 
 Then finally do python3 bruteforce_login_form.py