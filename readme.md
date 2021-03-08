# Server_Files.py

# Serve files via WIFI to hosts on the network using Python.

## Use this to transfer files to your phone or your friends computer.

Requirement:

Python3.4+


Run the serve_files.py script from the directory containing the files you wish to share.

```
$ python3 serve_files.py
```

Optionally, specify the ip address or port.

```
$ python3 server_files.py --host '192.168.12.34' 

$ python3 server_files.py --host '192.168.12.34' --port 1234
```

Output

```
~ $ python3 serve_files.py
Server is listening on 192.168.12.34 on port 1234.
```

From another device on the same network use a browser to navigate to IP address of where you are running your python server.
My laptop's IP address is 192.168.12.34 on port 1234 so on my phone I navigate to http://192.168.12.34:1234 .
