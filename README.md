omnitty
=======

a session tool for muti-connect the server


###Usage:
For CentOS:  
	
        yum -y install gcc
        yum -y install ncurses-devel

decompression all the three tarball and follow this sequence  

	rote-0.2.8 -> omnitty-0.3.0 -> omnitty-0.3.0-patched

just do the same:  
	
	./configure  
	make  
	make install  
	
after all of this, we need to export to system environment  

        echo "/usr/lib/rfmin/lib" >> /etc/ld.so.conf
        echo "/usr/lib/icc" >> /etc/ld.so.conf
        echo "/usr/local/lib" >> /etc/ld.so.conf
        ldconfig

Run `omnitty -T -W` 

