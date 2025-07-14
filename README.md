# linux-emulationstation


**On Debian/Ubuntu:**
All of this can be easily installed with `apt-get`:
```bash
sudo apt-get install libsdl2-dev libsdl2-mixer-dev libfreeimage-dev libfreetype6-dev \
  libcurl4-openssl-dev rapidjson-dev libasound2-dev libgl1-mesa-dev build-essential \
  libboost-all-dev cmake fonts-droid-fallback libvlc-dev libvlccore-dev vlc-bin libint-dev gettext git 
```

<br>

```bash
git clone --recursive https://github.com/JeversonDS/linux-emulationstation.git
```

<br>


```bash
cd linux-emulationstation
```

<br>

```bash
cmake .
```

<br>

```bash
make -j$(nproc)
```
