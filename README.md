## Build JOS Kernel


**Kernel**    
Download [Linux Kernel](https://kernel.org/) :    

	tar -xvf linux-x.y.z.tar.xz
	cp config linux-x.y.z/ 
	make menuconfig 
	make -j16 
