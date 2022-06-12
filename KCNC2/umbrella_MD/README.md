For the Umbrella sampling MD simulations the user would need to make separate directories for WT, V469L, V471L and then copy/move the files:
kcnc2.prmtop
prod.rsts
reference.crd
runprod.sb
window_*_*.rst7 into every directory.
** the channel coordinates range from 11A - 44.5 A.
** so window values are window_11_0.rst7 - window_44_5.rst7

Also, the values 'r2' and 'r3' in prod.rsts need to be changed to the target value for each window. 
For example, r2=r3=15.5 for window '15_5' etc.
