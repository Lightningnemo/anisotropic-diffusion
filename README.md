# anisotropic-diffusion

Anisotropic diffusion (AD) is employed to enhance the signal-to-noise ratio (SNR) of Brillouin distributed optical fiber sensor. A Brillouin optical time-domain analyzer (BOTDA)
with 99-km-long fiber under test is set up, where a section of 2.3 m and another 182 m section at the end of the fiber are heated for experimental verification. The SNR of 
experimental data sets with different sampling point numbers are enhanced to several improvement levels by AD and three other methods for comparison. Results show that the 
2.3 m section and the temperature transition region of the 182 m section are better preserved by AD than other methods for the same SNR improvement. Objective criteria 
analysis shows that AD achieves the best measured spatial resolution and temperature accuracy among the four methods, the location of temperature transition can be detected 
more accurately for data with low SPNs after AD denoising. In addition, the processing time of AD is 1/3 that of non-local means (NLM) and 6‰ that of block-matching and 3D 
filtering (BM3D). The edge-preserving quality and fast processing speed allow the proposed algorithm to be a competitive denoising alternative for sensors based on Brillouin 
scattering.


Please refer to the code:
https://github.com/michaelaye/pymars/blob/ca62a17c682f999c490cc0dbceb01433c385ced0/pymars/anisodiff2D.py
