# prueba1 REDHAT Benjamin Gonzalez Carlos Funez
repositorio para archivo de evaluacion numero 1 

creacion de la maquina virtual
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/264d6d83-d7e3-42cb-84da-76aeb0b9e322" />

creacion de el primera particion en sda EXT4 ocupando comando Mkfs.ext4 para restaurar la particion

<img width="1919" height="1072" alt="image" src="https://github.com/user-attachments/assets/760f4a3b-50db-4a61-b80b-abd2e7552ef8" />

dejamos la particion definitiva utilizando el comando VIM /etc/fstab

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/77712c50-c6ad-4ff7-a91f-2ecf497390e9" />

mount -a para montar la partcion numero 1 
<img width="1914" height="1074" alt="image" src="https://github.com/user-attachments/assets/ada58573-8673-4119-9534-02fdab2ba371" />

creacion del la segunda particion LVM ocupando comandos basicos como MKpart
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/bef4479b-1f44-486c-a67b-a46eb91cb173" />

creacion de la 3 particion con fichero XFS 
<img width="1919" height="1077" alt="image" src="https://github.com/user-attachments/assets/2d3c6738-8e73-4610-acdd-97bf462c9605" />

restauracion de la partcion numero 3 con mkfs.xfs /dev/sda3 y la creacion de los ficheros
<img width="1914" height="1064" alt="image" src="https://github.com/user-attachments/assets/19b09c2f-a599-4e54-911e-a3fe4f1806b7" />

disco numero 3 montado 
<img width="1919" height="1070" alt="image" src="https://github.com/user-attachments/assets/c8046bb1-1213-4c5e-94dc-42f5e1a4dd51" />

utilizando comando vim dejar definitiva la particion

<img width="1916" height="1079" alt="image" src="https://github.com/user-attachments/assets/c03f61b0-4d98-4910-a2ab-c4ef22398443" />

particion numero 4 montada 
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/c7ccc45d-b33e-4ef5-93fd-ddc9e8c101ef" 

reboot para que la particion se vea montada definitivamente montada sda1, sda3, sda4 
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/0eca1f0a-f61f-453d-9cfe-cc1d910a2162" />






