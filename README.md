# Dependencies
To install nasm and qemu

1. sudo apt update
2. sudo apt install nasm
3. sudo apt-get install qemu-system


# Create a binary file
nasm -f bin boot.asm -o boot.bin

# Run the emulator
qemu-system-x86_64 boot.bin