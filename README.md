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
openssl enc -aes-256-cbc -e -in [path-to-file-you-want-to-encrypt] -out [path-to-where-the-encrypted-file-will-be-saved]
```

Decrypt:
```
openssl enc -aes-256-cbc -d -in [path-to-file-you-want-to-encrypt] -out [path-to-where-the-encrypted-file-will-be-saved]
```


**OpenSSH secure file copy**

scp copies files between hosts on a network.
```
scp -i .ssh/[id_rsa] [filename] [username]@[IP]:/home/
```

**How to access mysql**

How to access mysql server on mac using command line:
```
mysql -u root -p 
```

**Extact the files **

```
tar -xzf filename.tar.gz
```