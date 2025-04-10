
# ATF and u-boot for philips-hy3000

- https://cmi.hanwckf.top/p/mt798x-uboot-usage

![](/u-boot.gif)

## Prepare

```
sudo apt install gcc-aarch64-linux-gnu build-essential flex bison libssl-dev device-tree-compiler qemu-user-static
```

## Build

```bash
chmod +x build.sh
SOC=mt7981 BOARD=philips_hy3000 ./build.sh
```

## Generate GPT with python2.7

```bash
sudo apt install python2.7
chmod +x generate_gpt.sh
./generate_gpt.sh
```
