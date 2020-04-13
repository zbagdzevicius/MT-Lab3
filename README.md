# MT-Lab3
LT
Šio laboratorinio darbo tikslas - sukurti pirmąją papildytos realybės (AR) taikomąją programėlę/aplikaciją.

Papildytos realybės programėlei sukurti galima rasti nemažai atviro kodo pavyzdžių. Vienas jų yra AR.js. Šio sprendimo taikymo pavyzdžių galima rasti čia: https://github.com/stemkoski/AR-Examples

# Reikalavimai susikurtai repozitorijai (angl. repository)
  - Turite susikurti esamos repozitorijos kopiją (angl. fork) ir sukurti du šakojimus (angl. branches): 'master' ir 'develop'.
  - 'develop' šakojime turi būti saugomi visi commit'ai, kurie atliekami kodo rašymo metu. Kai tik kodas atnaujinamas, tai turi būti užregistruota commit'e, parašant, kas pakeista ir, galbūt, kas dar neveikia.
  - Kai visas naujai pridėtas funkcionalumas veikia tinkamai, 'develop' šaklojimas turi būti sulietas (angl. merge) su 'master' šakojimu.
  
# Reikalavimai papildytos realybės programėlei
Galima rinktis iš kelių alternatyvų:
  - A alternatyva
    - Sukurkite 3D modelį naudojant Three.js ir integruokite į laboratorinio darbo pavyzdį.
    - Trimatis modelis turi turėti sudėtinę, jūsų pačių sukurtą struktūrą.
  - B alternatyva
    - Sukurkite savo nuosavą žymeklį.
    - Programėlė turėtų automatiškai aptikti žymeklį ir atvaizduoti trimatį elementą.
  - C alternatyva
    - Parodykite iniciatyvą ir sukurkite ką nors originalaus.
    - Pridėkite papildomo funkcionalumo esamam AR.js.
    - Sukurkite skirtingus markerius/žymeklius, skirtus valdyti garso ar vaizdo grotuvą.
    - Pridėkite savo sugalvotą valdymo funkcionalumą.
Visoms alternatyvoms galioja taisyklės (vertinimo kriterijai):
  - Išbandyti sukurtą grotuvą mažiausiai dviejose naršyklėse ir README.md parašyti, kuriose naršyklėse išbandyta ir veikia.
  - Įgyvendinus papildomą funkcionalumą, galima gauti papildomų balų.
  - Laboratorinis darbas užskaitomas, jei rezultate įgyvendinti bent du reikalavimai iš sąrašo  

# Svarbi informacija
  - Šio laboratorinio darbo pavyzdžiui paleisti reikalingas SSL.
  - Turite sugeneruoti self-signed tipo sertifikatą savo interneto (web) serveriui. 
  - Galite naudoti vieną iš šių serverių:  
    - Apache: https://www.raspberrypi.org/documentation/remote-access/web-server/apache.md 
    - Tomcat: http://androidsrc.net/installing-tomcat8-raspberry-pi-3/ 
    - HFS: http://www.rejetto.com/hfs/ or any other server.
  - Proxy http to https:
    - https://technique.arscenic.org/lamp-linux-apache-mysql-php/apache-le-serveur-http/modules-complementaires/article/installer-et-configurer-le-module-ssl-pour-apache2?fbclid=IwAR1_nXNQlrMIdJ5tilVUyr45xeiA91yw21vhnMxWHnuvY01VTd2FVR_T2ao  

EN
This lab aims to build your first Augmented Reality (AR) app.

There are many open source alternatives to build augmented reality application. One of the web based solution is AR.js. You can try a huge set of examples: 
https://github.com/stemkoski/AR-Examples

# Requirements for repository
  - You have to clone this repository and make two branches (master and develop).
  - The develop branch should contain commits of every new feature of the AR application.
  - When all features will be ready you have to merge the development branch to the master.

# Requirements for AR application
There are three options to choose from. 

Option A:
  - Create a 3D model using Three.js and integrate into laboratory sample. 
  - 3D model must be complex structure made by you.

Option B:
  - Make your own marker like 'Hiro'.
  - The application should be able to recognize your marker and display a cube when it is present.

Option C:
  - It is your chance to show your skills and creativity.
  - You can add extra features to existing AR.js examples.
  - Make different markers to control a video/audio player.
  - Or anything other.
  
The general requirements for option A, B & C:
  - Test application on at least two browsers and specify in README.md which version and browser it was.
  - To pass this lab, you have to fully complete an option.  
  
# Important notes
  - SSL server is needed to run this lab material.
  - You will be needed to generate self signed sertificate and set up your web server. 
You can try to use these file servers:  
  - Apache: https://www.raspberrypi.org/documentation/remote-access/web-server/apache.md 
  - Tomcat: http://androidsrc.net/installing-tomcat8-raspberry-pi-3/ 
  - HFS: http://www.rejetto.com/hfs/ or any other server.
Proxy http to https:
  - https://technique.arscenic.org/lamp-linux-apache-mysql-php/apache-le-serveur-http/modules-complementaires/article/installer-et-configurer-le-module-ssl-pour-apache2?fbclid=IwAR1_nXNQlrMIdJ5tilVUyr45xeiA91yw21vhnMxWHnuvY01VTd2FVR_T2ao  


Įgyvendinta A variantas. Aktyvuoti github pages su lets-encrypt serfitikatu by default, tai serverio paleidimo nereikia runninimui statinio turinio.
