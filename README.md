# SSFP_PulseSeqNMR
Phase alternation SSFP developed for high resolution spectral acquisition
Tiago Bueno de Moraes
tiagobuemoraes@gmail.com
University of São Paulo (USP) - Brazil.

; ############################################################################
; T.B. Moraes, et al.; Steady-State Free Precession sequences for high and low field 
; NMR spectroscopy in solution: Challenges and opportunities, JMRO, 2022.
; Quadratic phase increment SSFP (SSFPdxdt)
; 1D sequence with power-gated decoupling
; ############################################################################
; Set:  DS = 1 ; NS = 1;  d3 = Aq + d1; 
; Recommended values: d1 = 0.01001 ms (minimum); Aq = 0.189 ms; d3 = 0.2 ms;
; L0 - dummy scan of each phase increment block; 
; L1 - scan in each phase increment block;  L0 e L1 need to be multiple of the table phase;
