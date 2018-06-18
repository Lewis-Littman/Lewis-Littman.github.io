---
title: Bits and shifts
layout: post
author: lewis.littman
permalink: /bits-and-shifts/
source-id: 1KLeNT_7vurHyH6QoTI6Idwm_BkPUJ9LyvgMdz1JuPiA
published: true
---
**8-bits - **8 bit systems can hold a maximum of 256 things. This is because that you can't from 0. So 0-9 is actually 10 things (0, 1, 2, 3 , 4, 5, 6, 7, 8, 9). This means that 0-255 is 256 things.

8 bit = 256

16 bit = 65536

32 bit = 4294967296 

64 bit = 18,446,744,070,000,000,000 (10^19)

8 bits = 1 Byte           (The exam will accept using 1000 instead of 1024 which is easier to work out) 

1024 B = 1 kB

1024 kB = 1 mB

1024 mB = 1 GB

1024 GB = 1 TB

**Binary shift - **this is when you shift all the numbers to the left by one and adding on a zero to the end when multiplying by 2.

100101 x 2 = 1001010 (the same number just with a zero on the end)

You can also divide by 2 and the shift would occur in the opposite direction

100101 / 2 = 010010.1 (when the we go below 1 we use floating points to notify this)

**Floating points - ** in binary we cannot have precise decimal numbers as the past the floating point, it still follows the pattern 2^2 2^1 2^0 2^-1 2^-2 (For example ⅓ is not divisible exactly by 2 which means we can never exactly get ⅓ in binary)

