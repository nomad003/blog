+++
title = "OS"
tags = ["OS"]
date = "2022-12-02"
+++

# OS

## Backgroup
    operation system is a tool that can control machine and support API to user, then we can get the ability of computer through the OS.

## Boot
    BIOS detect the boot device, first sector in disk, which is 512 bytes, end with 0xAA55
    this first 512 bytes code loads the kernel to memory in specific place

    kernel start to execute

    some base knowledege point:
        16 bit real mode
            physical address = (segment register) << 4 + address
        32 bit protected mode 
            segment
                GDT
            page
                CR0
            physical address = data in PTT, PDT
            
## Context Swtich
    Context:
        Register
            
        Stack

    Interrupt:            
       Timer Interrupt 

    Current Context per CPU

## Memory
    Physical Address 
    Linear Address
    Virtual Address

## I/O


## End
