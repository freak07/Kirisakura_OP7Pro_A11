系统
docker pull amd64/ubuntu

使用的编译器
gcc-arm-linux-gnueabi
gcc-aarch64-linux-gnu
clang



编译指令
make O=out kirisakura_defconfig
make O=out

环境变量
export ARCH=arm64
export SUBARCH=arm64
export CROSS_COMPILE=aarch64-linux-gnu-
export CROSS_COMPILE_ARM32=arm-linux-gnueabi-
