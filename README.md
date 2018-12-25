```
Contact Me
Telegram：@myjsqmail
```

v2ray
```
https://github.com/v2ray/v2ray-core/
```

233 scripts
```
https://github.com/233boy/v2ray
```

adblock
```
https://github.com/h2y/Shadowrocket-ADBlock-Rules
```

guise web
```
https://github.com/blackrockdigital
```

caddy
```
https://github.com/mholt/caddy
```

tproxy script
```
https://github.com/zfl9/ss-tproxy
```

orange pi zero plus
```
install kernel hearder
wget https://beta.armbian.com/pool/main/l/linux-4.14.78-sunxi64/linux-headers-next-sunxi64_5.65.181102_arm64.deb
dpkg -i ./linux-headers-next-sunxi64_5.65.181102_arm64.deb 
cd /lib/modules/4.14.78-sunxi64/build/
make scripts
```

8188eu ap mode
```
https://github.com/lwfinger/rtl8188eu
git checkout -b v5.2.2.4 origin/v5.2.2.4
make && make install
```

orange pi
```
https://github.com/hyphop/miZy
https://dietpi.com/
https://archlinuxarm.org/
https://www.armbian.com/
https://openwrt.org
```

hostapd
```
git clone git://w1.fi/srv/git/hostap.git
git clone https://chromium.googlesource.com/chromiumos/third_party/hostap
```

eap_reauth_period
wpa_group_rekey

8189ftv
```
git clone https://github.com/jwrdegoede/rtl8189ES_linux.git
cd rtl8189ES_linux.git
git checkout -B rtl8189fs origin/rtl8189fs
make -j4 ARCH=arm CROSS_COMPILE=arm-linux-gnu- KSRC=../linux
```
8189etv && 8189es
```
git clone https://github.com/jwrdegoede/rtl8189ES_linux.git
cd rtl8189ES_linux.git
make -j4 ARCH=arm64 KSRC=/lib/modules/4.14.78-sunxi64/build
#make -C /lib/modules/4.14.78-sunxi64/build M=/root/rtl8189ES_linux.etv  modules
```

Realtek Drivers
```
git clone https://gitlab.com/ember-dev/EmbER-Amlogic-Realtek-Drivers.git
```

openwrt openssl
```
./libcrypto.so: warning: gethostbyname is obsolescent, use getnameinfo() instead.
./libcrypto.so: undefined reference to `getcontext'
./libcrypto.so: undefined reference to `setcontext'
./libcrypto.so: undefined reference to `makecontext'
./Configure linux-aarch64 --prefix=/root/tmp/openssl --openssldir=/root/tmp/openssl no-shared no-async
is need no-asm? i don't know.
是mipsel-linux没有提供GNU C的ucontext库
config 配置时添加 no-async
修改Makefile ,若有-m32或-m64 字段，直接删除
```

RTL8821CU_driver_v5.4.1
```
https://github.com/axiomware/RTL8821CU_driver_v5.4.1
```

RTL8821CU_driver_v5.2.15.3
```
https://github.com/axiomware/RTL8821CU_driver_v5.2.15.3
```
