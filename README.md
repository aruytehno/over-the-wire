![alt text](img/workplace.png "We're hackers, and we are good-looking. We are the 1%")

# OverTheWire
[overthewire.org](https://overthewire.org/)  
[Music](https://www.youtube.com/watch?v=72LUL1hhXdc)
### [Bandit](https://overthewire.org/wargames/bandit/)

```shell
sudo apt-get install sshpass
# sshpass -p your_password ssh user@hostname
```
Level 0

```shell
sshpass -p bandit0 ssh bandit0@bandit.labs.overthewire.org -p 2220
cat readme 
```

Level 1

```shell
sshpass -p NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL ssh bandit1@bandit.labs.overthewire.org -p 2220
cat ./-
```

Level 2

```shell
sshpass -p rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi ssh bandit2@bandit.labs.overthewire.org -p 2220
cat "spaces in this filename"
```