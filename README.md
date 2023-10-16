# 5025211251_MuhammadAhyunIrsyada_TugasTCP-UDP

##TCP 
###NO 1 

**Soal** 
What is the IP address and TCP port number used by the client computer (source) that is transferring the file to gaia.cs.umass.edu?

**Penyelesaian**

- Pertama tama cari IP dari `gaia.cs.umass.edu` dengan cara melakukan Ping di terminal

![ss](Bukti/tcp01.png)
  
- Lalu filter IP dari `gaia.cs.umass.edu` yang mana IPnya adalah `128.119.245.12` dengan script `ip.addr == 128.119.245.12`

![ss](Bukti/tcp02.png)
  
- Setelah melakukan trace maka IP address dari client computer adalah `192.168.43.28` dan menggunakan port 55965
