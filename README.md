# MBRBOMBER
MBRBOMBER is a FMV(Fun-Made-Virus) I coded that overwries your MBR with a message.
THIS PROGRAM IS NOT TO DAMAGE ANOTHER PERSONS!
Source code is made in C++ and in ASM.
#License
The use of this code is restricted,
so that means you can't do a few things.
YOU CAN'T SPREAD THIS VIRUS OR YOUR MODIFICATION.
YOU CAN'T USE THIS CODE FOR BAD PURPOSES
YOU CAN'T USE THIS PROGRAM AS YOUR CREATION
#How to create
First of all, click on Code>Download ZIP.
Once file has downloaded, open the solution.
If you want to add your own MBR, follow this steps:
1. Download provided ASM file
2. Open the ASM file
3. Go to line 40 and you'll find some text
4. Replace that text. Renember you can't delete 13, 10 or the "" or , 0
5. Save the ASM file
6. Download NASM Compiler from NASM.us
7. Install the program and go to %APPDATA%\Local\bin\NASM and copy your ASM file with the name MBR.asm
8. Run nasmpath batch file and type: nasm -f MBR.asm -o data.bin
9. Go to http://tomeko.net/online_tools/file_to_hex.php?lang=en and select your data.bin file
10. Copy the code that will appear
11. Paste the code onto line 207
12. Compile and DONE!
