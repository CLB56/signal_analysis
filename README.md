# Fourier Analysis

A program done in Basic language for TI89 which defines the an and bn coefficients of Fourier series. I programmmed it for electrical signal analysis.

The main advantage of this programm is that you can share the period into as many functions as needed.

For example, it would be possible to define such a signal :

For x ∈ [0;1[, f(x) = x

For x ∈ ]1;2[, f(x) = -2x+4

For x ∈ ]2;3[, f(x) = x-3

In this example the period is shared into 3 functions. But you can imagine more complex signals.

Some side features have been added : 
- Calculation of the root mean square value of the signal
- Calculation of the total harmonic distortion rate
- equations of fundamental frequency and harmonics
- Drawing of the signal considering n harmonics

It uses the TI89 formal solver to define exact values of the coefficients and Vertel library.

I can share the Vertel library upon request (developped by Zephyr). But, i don't think I have the right to host the library on this repo.

