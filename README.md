## twitter006 | #つぶやきProcessing 
![twitter](https://github.com/nicolasbaez/twitter006/blob/master/twitter006.gif)
```processing
#つぶやきProcessing float h,j,i,k,c,a=0;void setup(){size(512,256);h=255;noFill();}void draw(){translate(h,128);rotate(PI-(j/8));background(0);for(i=0;i&lt;8192;i+=8){k=map(i,0,8192,1,8);c=k*48;stroke(h-c);k=random(k);circle(((a+k)*cos(i/PI)),((a+k)*sin(i/PI)),k);a=i/24;}j+=0.125;}
```
