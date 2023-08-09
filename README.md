# Useful stuff


**By:** Wiz1101  <br>


<mark>**How to create a server with python:**</mark>

```
sudo python3 -m http.server 8000
```

**Other end (machine):**

```
localhost:8000
```


<mark>Network quality command:</mark>

```
$ networkquality
```

<mark>WiFi:</mark>

**How to get the current connection paswsword:**

```
$ security find-generic-password -wa [wifiname]
```

<mark>IP:</mark>

**To see your public IP address in the Mac Terminal, type:**

```
$ curl ifconfig.me
```

<mark>VPN:</mark>

**how to run vpn:**

```
$ export PATH=$PATH:/usr/local/Cellar/openvpn/2.6.5/sbin
$ openvpn
```

<mark>Executable files</mark>

**Path for exec files on mac:**

```
/usr/local/bin
```
<mark>Impacket .py files:</mark>

**Path for impacket files on mac:**

```
.local/pipx/venvs/impacket/bin
```

<mark>How to Encrypt/Decrypt Files:</mark>

**Encrypt:**
```
openssl enc -aes-256-cbc -e -in [path-to-file-you-want-to-encrypt] -out [path-to-where-the-encrypted-file-will-be-saved]
```

**Decrypt:**
```
openssl enc -aes-256-cbc -d -in [path-to-file-you-want-to-encrypt] -out [path-to-where-the-encrypted-file-will-be-saved]
```
