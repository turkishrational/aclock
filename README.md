## ANALOG CLOCK DEMOs FOR TRDOS 386
(Display Clock in Video MODE 13h) ((+ VESA VBE mode 105h))

.s files: 
         ASM Source code files in NASM format/syntax
         
.PRG files:
         TRDOS 386 program files.
         
.COM files:
         MSDOS COM (program) files.
         
.ASM files:
         ASM source code for MSDOS clock program.

a_test.img:
         1.44 MB bootable floppy disk image for TRDOS 386 test.

trdos386_aclock_qemu.zip:
         Sample QEMU emulator package to test/try.

## Samples:
   ACLOCK.COM : FPU based.
   
          MSDOS program written by Leonardo Ono. FPU (math instructions) based.
          
   ACLOCK.PRG : FPU based.
   
          TRDOS 386 adaptation of ACLOCK.COM. FPU based.
          
          Video and Keyboard functions (partially) are as (ROMBIOS type) interrupt service. 
          
   ACLOCK1.PRG : FPU based.
   
          Video and keyboard functions are as INT 40h (TRDOS 386 kernel service) calls.
          
   ACLOCK2.PRG : Sine/Cosine table based.
   
          ACLOCK.PRG modified as Sine/Cosine table based. Colored clock (CGA colors.)
          
          (without FPU instructions) -BEEP feaure (after pressing SPACEBAR key)-
          
          (ROMBIOS type interrupts. INT 32h == ROMBIOS INT 16h. INT 31h == ROMBIOS INT 10h.) 
          
   ACLOCK3.PRG:
   
          Modified ACLOCK2.PRG with INT 40h calls instead of (ROMBIOS type) interrupts.

   Erdogan Tan - October 2024
       
