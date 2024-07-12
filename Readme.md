# Pong-Os 🏓

> [!WARNING]
> Its not any os or even a kernel.
> Its just a bootsector program.
> I was learning to make operating system but then
> Before learning to read disk i though it would be good to make someting cool before i proceed further.
> then i thought about making a simple classical game like snake thinking about complexity to fit it in just 512 bytes i though to make a classical pong game clone.
> I havnt tested it on real hardware so dont cry to me if something goes wrong if you took the risk :D
> Also Game Over screen is missing as i exceeded 512bytes limit 😁
> For now it just goes into infinite loop and freezes after enemy scores `WIN_SCORE` defined in `include/CONSTANTS.asm`


## Dependencies 
- nasm assembler
- qemu or any other emulator / vm (should be intel x86 \ 8086 arch)


## Building Instruction ⚒

- `cd` into repo root
- `nasm -i include -f bin ./src/pong-os.asm -o pong-os.bin`

> [!NOTE]
> If on windows and using qemu just run `run.bat` file

## Running It ⚙

- Qemu users 
    - `qemu-system-x86_64.exe -full-screen ./pong-os.bin`
- Others
    - run it using your emulator / vm (you have to lead or burn generated binary to harddisk / virtual disk image)
    





