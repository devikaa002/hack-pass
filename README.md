# hack-pass
# **Password Cracking**

## **Goal**

Creating a password protected zip file and cracking it using john the ripper.

**Let&#39;s Do it**

So we can first create a zip file with some password

![](https://github.com/devikaa002/hack-pass/blob/main/zip.png)

So we are using john the ripper crack the password lets get the hash of the password of the zip file.

![](https://github.com/devikaa002/hack-pass/blob/main/hash1.png)

Let&#39;s save the hash in a file.

![](https://github.com/devikaa002/hack-pass/blob/main/hash2.png)

Let&#39;s crack the password

```
john hash.txt
john hash.hash
```
We wil get the cracked password.
