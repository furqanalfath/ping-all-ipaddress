# ping-all-ipaddress
Find / Ping all IP Address that connected. Note: This is assume you already know the subnet mask.

Code : FOR /L %i IN (1,1,254) DO ping -n 1 192.168.10.%i | FIND /i "Reply">>c:\ipaddresses.txt

Open Command Prompt and paste that code. 

Note: If not work try to write manually that code into Command prompt or open notepad and paste into that. Save it as .bat and run (click)

Source : http://stackoverflow.com/questions/13713318/ping-all-addresses-in-network-windows
