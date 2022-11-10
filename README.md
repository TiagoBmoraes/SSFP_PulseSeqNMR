# SSFP Pulse Sequences for NMR
Phase alternation SSFP developed for high resolution spectral acquisition
Tiago Bueno de Moraes
tiagobuemoraes [a] gmail.com
University of São Paulo (USP) - Brazil.

=============
; 
; T.B. Moraes, et al.; Steady-State Free Precession sequences for high and low field 
; NMR spectroscopy in solution: Challenges and opportunities, JMRO, 2022.
; Linear and Non-linear Phase increment SSFP: SSFPdx and SSFPdxdt
; 1D sequence with power-gated decoupling
; 
; Set:  DS = 1 ; NS = 1;  d3 = Aq + d1; 
; Recommended values: d1 = 0.01001 ms (minimum); Aq = 0.189 ms; d3 = 0.2 ms;
; L0 - dummy scan of each phase increment block; 
; L1 - scan in each phase increment block;  L0 e L1 need to be multiple of the table phase;

SSFPd2 - uses two block acquisition
SSFPd4 - uses four block acquisition
SSFPd8 - uses eight block acquisition
SSFPdxdt - non-linear phase increment with continuous acquisition

References
[1] Moraes, T.B.; et al.; Suppression of spectral anomalies in SSFP-NMR signal by the Krylov Basis Diagonalization Method, 
Journal of Magnetic Resonance, v. 243, p. 74-80, 2014.
https://doi.org/10.1016/j.jmr.2014.03.009

[2] Moraes, T.B.; Precessão Livre no Estado Estacionário com alternância de fase para RMN em alta e baixa resolução, 172 p.,
Tese (Doutorado em Física), Instituto de Física de São Carlos, Universidade de São Paulo (USP), 2016.

====================
If you have doubts or suggestions - please email:  tiagobuemoraes [a] gmail.com
https://sites.google.com/view/tiagomoraes
