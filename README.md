# ncbgrab
automated nc command to grab port banners.

# Install
1. Install parallel, mac: `brew install parallel`, Debian: `sudo apt install parallel`
2. `chmod +x ncbgrab`

# Run
`./ncbgrab -l ipandportlist.txt`

# Note!
The ips and ports should be in same file like this example of ipandportlist.txt:
```
1.1.1.1:443
1.1.1.1:80
1.1.1.1:25
1.1.1.1:22
1.1.1.1:9999
```
