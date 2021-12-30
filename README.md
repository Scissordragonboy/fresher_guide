# Script

```
 sudo su
```


```
 add-apt-repository ppa:openjdk-r/ppa
```
 
```
apt-get update && apt-get install bison build-essential curl ccache flex lib32ncurses5-dev lib32z1-dev libncurses5-dev libsdl1.2-dev libxml2 libxml2-utils lzop pngcrush schedtool squashfs-tools xsltproc zip zlib1g-dev git-core make gperf openjdk-8-jdk
```

```
exit
```


```
mkdir ~/bin && PATH=~/bin:$PATH && cd ~/bin && curl http://commondatastorage.googleapis.com/git-repo-downloads/repo >~/bin/repo && chmod a+x ~/bin/repo && git clone https://github.com/akhilnarang/scripts && cd scripts && bash setup/android_build_env.sh
 ```

Github profile config

```
 git config --global user.email "Scissordragonboy@gmail.com" &&  git config --global user.name "Scissordragonboy"
 ```

