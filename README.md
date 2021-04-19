# MIMO-RTS - HELP
MIMO Linear Time Invariant System Real Time Simulator

## 1 System settings

## 2 Transfer Function systems

### 2.1 Topology selection


### 2.2 Continuous-time

Continuous-time systems are defined using the numerator and denominator of transfer functions G1 and G2.  The maximum complete system order is 4, therefore order of G1 + order of G2 is maximum 4, in the form:

<img src="https://render.githubusercontent.com/render/math?math=G(s) = \frac{b_4s^4\+b_3s^3+b_2s^2+b_1s+b_0}{a_4s^4+a_3s^3+a_2s^2+a_1s+a_0}$">

The numerator and denominator with the numbers separated by space or comma.

Numerator formats to insert in the app:
  * Space separated values:    b4 b3 b2 b1 b0
  * Comma separated values:    b4, b3, b2 , b1, b0

Denominator formats to insert in the app:
  * Space separated values:   a4 a3 a2 a1 a0
  * Comma separated values:   a4, a3, a2, a1, a0

Example 1: numerator or denominator s²+4s+2:
  * Space separated values:   1 4 2
  * Comma separated values:   1,4, 2

Example 2:  G(s) = 4  (gain, order 0):
  * Numerator:   4
  * Denominator:   1



### 2.3 Discrete-time


## 3 State space systems


### 3.1 Continuous-time


### 3.2 Continuous-time


## 4 System saving to device and verification


## 5 Limitations
