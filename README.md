# Useful stuff


**By:** Wiz1101  <br>


**How to create a server with python:**

```
sudo python3 -m http.server 8000
```

Other end (machine):

```
localhost:8000
```


**Network quality command:**
```
networkquality
```

**WiFi:**

How to get the current connection paswsword:

```
security find-generic-password -wa [wifiname]
```

**IP:**

To see your public IP address in the Mac Terminal, type:

```
curl ifconfig.me
```

**VPN:**

how to run vpn:

```
export PATH=$PATH:/usr/local/Cellar/openvpn/2.6.5/sbin
openvpn
```

**Executable files**
Path for exec files on mac:

```
/usr/local/bin
```
**Impacket .py files:**

Path for impacket files on mac:

```
.local/pipx/venvs/impacket/bin
```

**How to Encrypt/Decrypt Files:**

Encrypt:
```
openssl enc -aes-256-cbc -e -in [fileName] -out [fileName]
```

Decrypt:
```
openssl enc -aes-256-cbc -d -in [fileName] -out [fileName]
```


**OpenSSH secure file copy**

scp copies files between hosts on a network.
```
scp -i .ssh/[id_rsa] [filename] [username]@[IP]:/home/
```

**How to access mysql**

How to access mysql server on mac using command line:
```
/usr/local/mysql/bin/mysql -u root -p 
```

**How to get Default Port on mysql**
   
```
mysql> SHOW GLOBAL VARIABLES LIKE 'PORT';
```


**Extact the files**

```
tar -xzf filename.tar.gz
gzip -d filename.gz
```

**Find the files**

```
sudo find -type f -name "FILE_NAME" 2>/dev/null
```

**FFmpeg**

```
.mkv -> .mp4
ffmpeg -i "input.mkv" -c copy "output.mp4"

.mp4 -> .gif
ffmpeg -i sample.mp4 -filter_complex "[0:v] framestep=2,split [a][b];[a] palettegen=stats_mode=diff [p];[b][p] paletteuse=dither=bayer:bayer_scale=5:diff_mode=rectangle" output.gif
```
