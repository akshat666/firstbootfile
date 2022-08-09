# Dependencies
To install nasm and qemu 
sudo apt update
sudo apt install nasm
sudo apt-get install qemu-system


# Create a binary file
nasm -f bin boot.asm -o boot.bin

# Run the emulator
qemu-system-x86_64 boot.bin