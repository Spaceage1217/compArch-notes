# Lecture 4 comp arch *2/5/2018*

## What are the three classes of instructions
 - Arithmetic
 - Branch
 - Memory

## Number of Operand
  - 3 operands allows for more flexibility vs operation cost.
    - more instructions when using 2 operands vs 3 operands
    - `add $3 $1 $2` vs ` add $3 $2`


## Why Immediate instructions?
  - Used for small constants that are often found in code.
   - like 0

  ##### Possible approaches?
    - put typical constants in memory and load them
    - create hard-wired registers like $zero
    - Have special instructions that contain constants.

  ##### Some trade offs?
    - lose space in registers

## What is the largest integer constant we can use in a C program?
  - Usually 2<sup>32</sup>
  - 32 bits are required

## Just add more registers right?
  - Wrong more registers require more space.
  - Register files with more locations are slower
