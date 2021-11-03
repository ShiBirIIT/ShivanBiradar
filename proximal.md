```matlab:Code
clc
clear all
close all
z = [-2.5 -1.5 0 1.5 2.5];
x = -3:0.01:3;
figure(1)
plot(x,abs(x));
ylim([-1 6]);
hold on
grid on
for i=1:1:length(z)
%     f1 = abs(z(i))
      f1 = abs(z(i)); 
    f2 = (z(i)-x).^2;
f = f1 + f2;
plot(x,f)
hold on
end
```

![/Users/shivanagoudabiradar/Desktop/untitled_images/figure_0.png
](https://github.com/ShivanB/Shivan-Biradar/blob/master/figure_0.png
)
