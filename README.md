# IceSheetFDM
Short lecture on Finite-Difference Method for modeling ice sheet flow

This github repository includes the jupyter notebook about the ice sheet finite-difference method. The details of the derivation of the ice flow equation and numerical method are derived in class (on the whiteboard).
Feel free to use the code and play around with it. For example: \\
(1) Investigate issues of numerical stability. How do the time step and the spatial resolution affect the stability of the model? How can you relate the Courant–Friedrichs–Lewy condition to this problem? \\
(2) Vary the values of the ice rheology parameter (bigA in the code). Does it change the time needed to reach a steady-state? Does it affect the ice sheet profile? \\
(3) Change the accumulation rate (bdot in the code). Try to implement a space-dependent accumulation rate. \\
Etc. \\

The notebook is in the file iceSheet_v0.ipynb. The first part of the notebook is a summary of the derivations that we made in class. The second part of the notebook is the model code. 

Any questions: vverjans3@gatech.edu
