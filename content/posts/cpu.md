+++
title = "CPU"
tags = ["CPU"]
date = "2022-12-01"
+++

# CPU

## Backgroud    
   Nowadays we see a lot of electronic products around us, which have powerful computing.How does it work? We may say it's due to they all have CPU in it. Then how does cpu works, and how we build a cpu step by step in history. We will dig into it, and try to build it from scratch. 

## Theoretical Basis
   a. Turing Machine 
        A machine that can compute automatically by a series of constructions, that the machine can recognize. With the input constructions executed, the machine change his inner state, and then finally it generate output, that people expected.
   b. Boolean Algebra
        AND OR NOT
        Logic Gates

## Physical World
    Electronic
    Electron negative potential
    Proton positive potential

## Start From Switch
### 1. Switch
    a. Switch
        Switch open circuit conduction
        Relay
        Do logic calculation
    b. Gate
        AND
        OR
        NOT
    c. Adder
        Complement

### 2. Add time in it
    a. oscillator clock
        repeated 10101010 frequency
    b. latch flip-flop
        feedback 
        output back to input
        d flip-flop
        d latch
        rs flip-flop

### 3. Multi bit
    a. Register

### 4. Construction
    Load
    Store
    Add
    Subtract
    Jump
    Halt

### 5. ALU

### 6. Control Unit

### 7. PC

### 8. Memory

### 9. I/O

## Finally
    CPU execute a series of instructions stored by memory, fetched to PC, control unit decode the instruction and execute it(1 or 0 electronic signal flow). the instruction may load data, store data, simple calution. after one instruction, follow another by PC+1 or jump instruction to the specific address. then loop it.
