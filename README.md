# matlab-1-phase
clc;
clear all;
d=input('enter the value of distnce between neutral and phase wire');
r=input('enter the value of radius of phase and neutral wire');
l=2*(10^-7)*log(d/r);
c=(2*3.14*8.85*(10^-12))/log(d/r);
fprintf('\n value of inducatnce=%d h/m \n',l);
fprintf('\n value of capacitance=%d f/m \n',c)
