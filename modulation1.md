clc;
clear all;
close all;
a=5;
fm=2;
t=0:0.001:2;
sm=a*sin(2*pi*fm*t);
subplot(3,1,1);
plot(t,sm);
grid on;
fc=20;
sc=a*sin(2*pi*fc*t);
subplot(3,1,2);
plot(t,sc);
mi=1;
sfm=(a+mi*sm).*sin(2*pi*fc*t);
subplot(3,1,3);
plot(t,sfm);
