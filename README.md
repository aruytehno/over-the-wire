![alt text](img/workplace.png "We're hackers, and we are good-looking. We are the 1%")

# OverTheWire
[overthewire.org](https://overthewire.org/)  
[Music](https://www.youtube.com/watch?v=72LUL1hhXdc)
### [0 Bandit](https://overthewire.org/wargames/bandit/)

```shell
sudo apt-get install sshpass
sshpass -p your_password ssh user@hostname
```

<details><summary>Level 0</summary>
<p>
  
```shell
sshpass -p bandit0 ssh bandit0@bandit.labs.overthewire.org -p 2220
```
```shell
bandit0
```
 
```console  
bandit0@bandit:~$ cat readme 
```
  
```console  
boJ9jbbUNNfktd78OOpsqOltutMc3MY1
```
  
</p>
</details>

<details><summary>Level 0 → Level 1</summary>
<p>

  
```shell
ssh bandit1@bandit.labs.overthewire.org -p 2220 
``` 
```shell
boJ9jbbUNNfktd78OOpsqOltutMc3MY1
```
  
```console
bandit1@bandit:~$ cat readme 
```
  
</p>
</details>