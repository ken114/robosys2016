# robosys2016
robosys2016の課題

#動作
1秒間で徐々にLEDが明るくなっていき、1秒間で徐々に暗くなっていく

#使い方
1. $make
2. $sudo insmod myled.ko
3. $sudo chmod 666 /dev/myled0
4. $echo 2 > /dev/myled0
5. $sudo rmmod myled
6. $make clean

#動画
https://youtu.be/dxOV5e0sRcI
