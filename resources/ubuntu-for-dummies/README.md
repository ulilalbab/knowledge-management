# Ubuntu For Dummies

## Ubuntu Won't Boot

Have a problem when we want to use dual boot. After Windows was installed, ubuntu was not detected.

[https://www.makeuseof.com/tag/fix-ubuntu-linux-pc-wont-boot/\#:~:text=One%20of%20the%20most%20common,correct%20boot%20device%20is%20selected.](https://www.makeuseof.com/tag/fix-ubuntu-linux-pc-wont-boot/#:~:text=One%20of%20the%20most%20common,correct%20boot%20device%20is%20selected.) 



## Change Directory

Remember that linux is case sensitive

```bash
cd ~/Downloads
```

## Install Package

After Download the package, we need to install it by using terminal

Go to directory of file

Replace \* with packaged name

```bash
sudo dpkg -i *.deb
```

## Uninstall Package

Change keyword to package name that we want to remove

```bash
$ dpkg –l | grep keyword
```

## Update Kernel

After struggle to find out how to change brigthness for my laptop. Finally I can update kernel from Ubuntu 20.04. Previously, I am using kernel version 5.4, then I upgraded it to 5.9.

The way that work for me use the repository below

{% embed url="https://github.com/bkw777/mainline" %}

```bash
sudo add-apt-repository ppa:cappelikan/ppa
sudo apt update
sudo apt install mainline
```



### Install .sh File

1. Change Directory file location

```bash
chmod +x install.sh
sudo ./install.sh

```

## 

## Getting Super Powers

Becoming a super hero is a fairly straight forward process:

```
$ give me super-powers
```

{% hint style="info" %}
 Super-powers are granted randomly so please submit an issue if you're not happy with yours.
{% endhint %}

Once you're strong enough, save the world:

{% code title="hello.sh" %}
```bash
# Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```
{% endcode %}



