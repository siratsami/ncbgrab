# ncbgrab
automated nc command to grab port banners.

# Install
1. Install parallel, mac: `brew install parallel`, Debian: `sudo apt install parallel`
2. `chmod +x ncbgrab`

# Run
```
$ ./ncbgrab -l ipandportlist.txt                                                                                                        [14:22:40]
Banner for 1.1.1.1:80:
Connection to 1.1.1.1 port 80 [tcp/*] succeeded!
-----------------------------
Banner for 1.1.1.1:443:
Connection to 1.1.1.1 port 443 [tcp/*] succeeded!
<html>
<head><title>400 The plain HTTP request was sent to HTTPS port</title></head>
<body>
<center><h1>400 Bad Request</h1></center>
<center>The plain HTTP request was sent to HTTPS port</center>
<hr><center>cloudflare</center>
</body>
</html>
-----------------------------
```

# Note!
The ips and ports should be in same file like this example of ipandportlist.txt:
```
1.1.1.1:443
1.1.1.1:80
1.1.1.1:25
1.1.1.1:22
1.1.1.1:9999
```
