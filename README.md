Docker
======

## *Apa Docker?*

Docker adalah salah satu platform yang dibangun berdasarkan teknologi container. Docker merupakan sebuah project open-source yang menyediakan platform terbuka untuk developer maupun sysadmin untuk dapat membangun, mengemas, dan menjalankan aplikasi dimanapun sebagai sebuah wadah (container) yang ringan. Dengan sangat populernya docker, sebagian orang sering menganggap docker adalah sebutan lain untuk container.

## *Docker - Orchestration using Docker Compose*

Pada pertemuan ke-12 ini kita mempraktikkan bagaimana mengatasi masalah menggunakan Docker ketika bekerja dengan beberapa kontainer, dan kita kesulitan untuk mengelola starting bersama dengan konfigurasi variabel dan link. 

###  https://www.katacoda.com/courses/docker/11

#### Step 1 - Defining First Container

Dalam skenario ini, kita memiliki aplikasi Node.js yang memerlukan koneksi ke Redis. Untuk memulai, kita perlu mendefinisikan file docker-compose.yml untuk meluncurkan aplikasi Node.js.
 
 ![logo](https://github.com/riskalest/Tct_Per_12_Docker/blob/master/Step_1.PNG)
 
#### Step 2 - Defining Settings

Docker compose digunakan untuk menjalankan semua service yang dijalankan dalam docker.

 ![logo](https://github.com/riskalest/Tct_Per_12_Docker/blob/master/Step_2.PNG)
 
#### Step 3 - Defining Second Container

Pada langkah sebelumnya, kita menggunakan Dockerfile di direktori saat ini sebagai basis untuk penampung. Pada langkah ini, kita ingin menggunakan image dari Docker Hub sebagai wadah kedua.

 ![logo](https://github.com/riskalest/Tct_Per_12_Docker/blob/master/Step_3.PNG)
 
#### Step 4 - Docker Up

 ![logo](https://github.com/riskalest/Tct_Per_12_Docker/blob/master/Step_4.PNG)
 
#### Step 5 - Docker Management

 ![logo](https://github.com/riskalest/Tct_Per_12_Docker/blob/master/Step_5.PNG)
 
#### Step 6 - Docker Scale

 ![logo](https://github.com/riskalest/Tct_Per_12_Docker/blob/master/Step_6.PNG)

#### Step 7 - Docker Stop

 ![logo](https://github.com/riskalest/Tct_Per_12_Docker/blob/master/Step_7.PNG)
 
 ![logo](https://github.com/riskalest/Tct_Per_12_Docker/blob/master/end.PNG)
 
 
#### Terimakasih :)


REFERENSI :
===========
https://www.katacoda.com/courses/docker/11
