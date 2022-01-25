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
mkdir ~/bin && PATH=~/bin:$PATH && cd ~/bin && curl http://commondatastorage.googleapis.com/git-repo-downloads/repo >~/bin/repo && chmod a+x ~/bin/repo && git clone https://github.com/akhilnarang/scripts && cd scripts && bash setup/android_build_env.sh && . b*/e* && lunch lineage_miatoll-userdebug && brunch lineage_miatoll-userdebug
 ```
 
# After finished build environment

```
mkdir octavi
```

```
cd octavi
```

# Then config your github identity

Github profile config


```
 git config --global user.email "Scissordragonboy@gmail.com" &&  git config --global user.name "Scissordragonboy"
 ```

# Download rom source now

```
repo init -u https://github.com/Octavi-OS/platform_manifest.git -b 12 --depth=1
```

# then sync source code
```
repo sync -c -f --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j8
```

# Github is ghey now

```
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
```

# Ccache build issues with roms

```
mkdir -p /tmp/ccache && export CCACHE_DIR=/tmp/ccache && export CCACHE_EXEC=$(which ccache) && export USE_CCACHE=1 && ccache -M 40G && ccache -z
```

# MEGA DOWNLOAD FROM TERMINAL LINE

```
megadl 'https://mega.nz/#!KWp1lQpD!x1yUoWsjkzjefYPlB8HePBD-OE1NjwzU0Up1tUTv2Jk'
```

# MEGA UPLOAD FROM TERMINAL LINE

```
sudo apt install ruby gem
```

```
gem install rmega
```

```
rmega-up filename -u gmail-id
```

# SOURCEFORE UPLOAD COMMAND LINE

```
sftp teamslow@web.sourceforge.net
```

```
cd /home/frs/project/Scissordragonboyrelease/Miatoll/Crdroid
```










# 
