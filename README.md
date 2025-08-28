# FM
PROGRAM 
```
Am = 4.2
fm = 368;
Ac = 8.4;
fc = 3680;
fs = 36800;
t=0:1/fs:2/fm;
m = Am*cos(2*3.14*fm*t);
subplot(3,1,1);
plot(t,m);
c = Ac*cos(2*3.14*fc*t);
subplot(3,1,2);
plot(t,c);
s = Ac*cos(2*3.14*fc*t + 5.2*sin(2*3.14*fm*t));
subplot(3,1,3);
plot(t,s);
```
WAVEFORM 






