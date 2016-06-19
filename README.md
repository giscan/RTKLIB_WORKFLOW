# RTKLIB WORKFLOW
A complete Workflow for RTKLIB (Work in progress)

# Specific installation : 

* Archlinux installation :
https://github.com/giscan/rtklib_pkgbuild


# 1) Basics and process to test your device (WIP)
rtkrcv (WIP : need to explain rtkcv.conf)

convbin file.ubx 

rnx2rtkp -o out.pos -p 0 file.obs file.nav 


# 2) Base + rover on a known point in real time over radio (WIP)
rtkrcv for rover

str2str for base

rnx2rtkp for processing


# 3) Base + rover with real time Ntrip corrections (need internet connection)
(WIP)

# 4) Base + rover with corrections in post
(WIP)

# How to get corrections :

In many case, French geographic local provider give you corrections (sometimes you have to pay) 

Official Ntrip webpage : https://igs.bkg.bund.de/ntrip/index

IGS corrections : 
http://wiki.openstreetmap.org/wiki/RTKLIB#Collecting_base_station_data_in_real-time

French local correction :
http://rgp.ign.fr/DONNEES/diffusion/#FTP

Need to investigate if we could use these corrections with ublox module :

http://www.trimblertx.com/uploadform.aspx

http://sopac.ucsd.edu/scout.shtml

http://www.ppp-wizard.net/ssr.html

http://www.ga.gov.au/bin/gps.pl

# Share your base with others : 
An interesting project : https://github.com/charlesrwest/pylonGPS

# Complete low cost building of RTK base + rover GNSS L1 : 

I help to build this project : 

https://github.com/Francklin2/RTKLIB_Touchscreen_GUI

Note : Could be improved with L1/L2 devices

# Ressources :

https://habrahabr.ru/post/244475/

http://wiki.openstreetmap.org/wiki/RTKLIB

http://cours-fad-public.ensg.eu/course/view.php?id=85

http://marcotte-ag.no-ip.org:8080/geomatic/

https://github.com/drotek/SMARTNAV-RTK/wiki

Discussion I start and interesting information (in french) : http://www.forumsig.org/showthread.php/41183-RTKlib-Retours-d-utilisateurs

