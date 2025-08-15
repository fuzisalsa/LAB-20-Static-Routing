# LAB-20-Static-Routing
tanggal 15 agustus 2025
# Mengkonfigurasi Static Routing dan basic configuration 

![M](grizly.png)

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

3. masukan dst-address dan gateway  
   pilih menu IP > routes    
   dst-addres= ip laptop B    
   gateway= ip yang akan di pasang di router2  

![M](lab22rot.PNG)

**R2**  
1. colokkan R2 ke laptop buka winbox  
   pilih menu terminal buatkan password dan user lalu identity  

![M](LAB22NM2.PNG)

2. masukan ip address untuk eth1 dan eth2    
   pilih Menu IP > Address  
   klik +  

![M](LAB22DRS.PNG)

3. masukan dst-address dan gateway  
   pilih menu IP > routes
   
         1. dst-addres= ip laptop A  
            gateway= ip router1  

![M](LAB22ROT2.1.PNG)


         2. dst-addres= ip laptop B  
            gateway= ip yang akan di pasang di router3  

![M](LAB22ROT2.PNG)

4. setting ip laptop A

![M](lab22ws.PNG)

5. ping ke ip laptop B

![M](pc2lab22.PNG)
