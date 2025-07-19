# ATF and u-boot for mt798x

## About bl-mt798x
- https://cmi.hanwckf.top/p/mt798x-uboot-usage

## Prepare

```
sudo apt install gcc-aarch64-linux-gnu build-essential flex bison libssl-dev device-tree-compiler qemu-user-static
```
基于2k+128分支为华邦的512M闪存添加支持

## Build
```
Usage:
eg: SOC=mt7981 BOARD=cudy_tr3000 MULTI_LAYOUT=0 ./build.sh //单一的大分区490M

eg: SOC=mt7981 BOARD=cudy_tr3000 MULTI_LAYOUT=1 ./build.sh //多分区，最大490M

```

![](/u-boot.gif)