# Docker



{% embed url="https://docs.docker.com/engine/install/ubuntu/" %}



**SET UP THE REPOSITORY**

1. Update the `apt` package index and install packages to allow `apt` to use a repository over HTTPS:

   ```text
   $ sudo apt-get update

   $ sudo apt-get install \
       apt-transport-https \
       ca-certificates \
       curl \
       gnupg-agent \
       software-properties-common
   ```



