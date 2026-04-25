# Lambda Lib
**Standard and core library for lambda**


## Core

### Imath

adds the following methods to all integers if applicable:

|       Name       |                                              Description                                              |
|:----------------:|:-----------------------------------------------------------------------------------------------------:|
|      abs()       |                         signed only, returns the absolute value of an integer                         |
|      sqrt()      | returns the square root of a number, negating if the input is also negative to denote complex results |
| clamp(min, max)  |                                clamps an integer between `min`, `max`                                 |
| pow(pow: uint32) |                                    raises n to the power of `pow`                                     |
|    log(base)     |                           returns the logarithm base `base` of the integer                            |
|     ln(base)     |                             returns the natrual logarithm of the integer                              |
|      log2()      |                             returns the logarithm base `2` of the integer                             |
|     log10()      |                            returns the logarithm base `10` of the integer                             |
|    min(other)    |                             returns the minimum between itself and other                              |
|    max(other)    |                             returns the maximum between itself and other                              |
|      even()      |                                  returns true if the number is even                                   |
|      odd()       |                                   returns true if the number is odd                                   |
|     signum()     |                                 returns 1 if positive, -1 if negative                                 |
|    positive()    |                                returns true if the number is positive                                 |
|    negative()    |                                returns true if the number is negative                                 |
