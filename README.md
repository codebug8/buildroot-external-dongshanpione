 
 > wget https://buildroot.org/downloads/buildroot-2021.02.8.tar.bz2
 
 > tar -xf  buildroot-2021.02.8.tar.bz2
  
 > git clone https://github.com/100askTeam/buildroot-external-dongshanpion
 
 > cd  buildroot-2021.02.8
  
 > make  BR2_EXTERNAL=../buildroot-external-dongshanpione/ dongshanpi1_defconfig
 
 > make
