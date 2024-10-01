** ANALOG CLOCK DEMOs FOR TRDOS 386 **

.s files: ASM Source code files in NASM format/syntax
.PRG files: TRDOS 386 program files
.COM files: MSDOS COM (program) files.
.ASM files: ASM source code for MSDOS clock program.

Samples:
   ACLOCK.COM : MSDOS program written by Leonardo Ono. FPU (math instructions) based.
   ACLOCK.PRG : TRDOS 386 adaptation of ACLOCK.COM. FPU based.
       Video and Keyboard functions (partially) are as (ROMBIOS type) interrupt service. 
   ACLOCK1.PRG : FPU based.
       Video and keyboard functions are as INT 40h (TRDOS 386 kernel service) calls.
   ACLOCK2.PRG : ACLOCK.PRG modified as Sine/Cosine table based.
                (without FPU instructions) -BEEP feaure (after pressing SPACEBAR key)-
                                          - CGA colors -
       (ROMBIOS type interrupts. INT 32h == ROMBIOS INT 16h. INT 31h == ROMBIOS INT 10h.)                              
   ACLOCK3.PRG: Modified ACLOCK2.PRG with INT 40h calls instead of (ROMBIOS type) interrupts.

   Erdogan Tan - October 2024
       
