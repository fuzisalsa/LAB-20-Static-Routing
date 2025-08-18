# LAB-20-Static-Routing
tanggal 15 agustus 2025
# Mengkonfigurasi Static Routing dan basic configuration 

![M](TOLGI.png)

**langkah-langkah:**  
**R1**
1. colokkan R1 ke laptop buka winbox     
   pilih menu terminal buatkan password dan user lalu identity    

![M](lab22pw.PNG)

![T](LAB22IDN.PNG)

LOGIN:  

![M](lab22mask.PNG)

2. masukan ip address untuk eth1 dan eth2    
   pilih Menu IP > Address  
   klik +  

![M](lad22adresPNG.PNG)

3. konfigurasi static routing 
   pilih menu IP > routes    

![m](iprutr1.PNG)

![m](iprutr11.PNG)


**R2**  
1. colokkan R2 ke laptop buka winbox  
   pilih menu terminal buatkan password dan user lalu identity  

![M](LAB22NM2.PNG)

2. masukan ip address untuk eth1 dan eth2    
   pilih Menu IP > Address  
   klik +
   
![M](ipr2.PNG)

4. konfigurasi static routing  
   pilih menu IP > routes

![m](iprutr2.PNG)

**R3**  
1. colokkan R2 ke laptop buka winbox    
   buatkan password dan user lalu identity  
   system > users  
   system > identity    

![M](usradd.PNG)

![M](id.PNG)

LOGIN

![M](logon.PNG)

2. masukan ip address untuk eth1 dan eth2      
   pilih Menu IP > Address    
   klik +
   
![M](ipr3.PNG)

4. konfigurasi static routing    
   pilih menu IP > routes

![m](iprutr3.PNG)

**R4**  
Dirouter 4, kita akan coba konfigurasi mengunakan mode CLI.  
1. Buat username dan password sesuai perintah di Topologi.  

         user add name=ahnaf password=jaringan group=full

2. Ganti Identitas RB menjadi R4.  

          system identity set name=R4
     
3. Tambahkan IP Address untuk ether1 dan ether2.  

 ![m](ipr4.PNG)

4. Sekarang konfigurasi static routing

![m](iprutr4.PNG)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# pengujian
**setting ip laptop A**  

![M](lab22ws.PNG)

**setting ip laptop B**  

 ![M](pc1.PNG)


tracert dan ping ke pc B

![N](lab22ping.PNG)

tracert dan ping ke pc A

![m](cmdsd.PNG)



# kesimpulan
Jadi, Static routing adalah konfigurasi jaringan di mana jalur data antar perangkat jaringan ditentukan secara manual. Static routing tidak akan berubah kecuali diubah.
