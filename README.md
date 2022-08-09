# Dependencies
To install nasm and qemu \n
sudo apt update \n
sudo apt install nasm \n
sudo apt-get install qemu-system \n


# Create a binary file
nasm -f bin boot.asm -o boot.bin

# Run the emulator
qemu-system-x86_64 boot.bin