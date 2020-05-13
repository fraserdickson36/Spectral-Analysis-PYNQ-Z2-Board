*****************************
*Group L - Spectral Analysis*
*****************************
Installation:
This repository contains the .tcl, .bit, .hwh files required for use with the PYNQ Z2 Xilinx Development board, along with the images to view on the Notebook. 
The contents of the .zip must be downloaded and extracted to the working directory of the board for the Jupyter Notebook to access them.

Description:
The purpose of the PYNQ design was to analyse a spectrum of signals using hardware acceleration of the Fast Fourier Transform (FFT). 
The user can select whatever frequency they want using a slider widget. 
The signal is then displayed through various window functions (Hann, Hamming and Blackman) so that the data can be analysed. 
The user can then also select the window they wish to apply before the signal is sent through the Fast Fourier Transform, implemented on the board hardware.
The user can then visualise the output plot, allowing them to see the frequency spectrum of the signal that they input.

User Guide:
1. Select Frequency to input using slider and arrow keys on keyboard.
2. Visualise the several plots of various windows.
3. Select which window you wish to apply to signal.
4. Run the signal through the hardware FFT & Magnitude.
5. Visualise the output from the buffer, viewing the spike at the chosen frequency.

Authors:
Fraser Dickson.
Andrew Clark.
Sean Heaney.

GitHub Link:
https://github.com/fraspop4236/Spectral-Analysis-PYNQ-Z2-Board
