---
description: Resources related with Machine Learning
---

# Machine Learnig

Anaconda Installation

Reference: [https://linuxize.com/post/how-to-install-anaconda-on-ubuntu-20-04/](https://linuxize.com/post/how-to-install-anaconda-on-ubuntu-20-04/)

Install Navigator

{% code title="Anaconda Navigator is a QT-based GUI." %}
```text
sudo apt install libgl1-mesa-glx libegl1-mesa libxrandr2 libxrandr2 libxss1 libxcursor1 libxcomposite1 libasound2 libxi6 libxtst6
```
{% endcode %}

{% code title="Download the Anaconda installation script " %}
```text
wget -P /tmp https://repo.anaconda.com/archive/Anaconda3-2020.11-Linux-x86_64.sh
```
{% endcode %}

Install as Normal User

```text
cd /tmp/
./

bash /tmp/Anaconda3-2020.11-Linux-x86_64.sh





```

Default Installation

```text
Anaconda3 will now be installed into this location:
/home/linuxize/anaconda3

    - Press ENTER to confirm the location
    - Press CTRL-C to abort the installation
    - Or specify a different location below
```

To activate the Anaconda installation, you can either close and re-open your shell or load the new `PATH` environment variable into the current shell session by typing:

```text
source ~/.bashrc

# Conda Navigator
anaconda-navigator
```









