# GIS_Shapefile_2020_ID (Completed)
DAGRI Updated Shapefiles - 30 June 2020

![Tableau 2020 Test](https://github.com/akirawisnu/GIS_Shapefile_2020_ID/blob/main/WhatsApp%20Image%202021-02-24%20at%2018.39.45.jpeg)
![QGIS 3.16 Test](https://github.com/akirawisnu/GIS_Shapefile_2020_ID/blob/main/Eu_qQJgUUAExlt8.jpg)

Updated GIS data (shapefiles) from Kemendagri DUKCAPIL Server (https://gis.dukcapil.kemendagri.go.id), they consist Province, District, Sub-District and Village level shapefile dataset. Feel free to use the file. 

Notes:
* The Geo ID is using DAGRI code, therefore will need to use concordance between BPS and DAGRI code. You can find the concordance under this link: https://sig-dev.bps.go.id/webgis/pencariankodenama
* There are 83 thousands Village (Desa + Kelurahan) in this data, which is inline with BPS own data, Village Potential 2018 (PODES 2018) https://www.bps.go.id/pressrelease/2018/12/10/1536/hasil-pendataan-potensi-desa--podes--2018.html

It consists information of:
* number of districts (jumlah_kab)
* number of sub-districts (jumlah_kec)
* number of village (jumlah_kel)
* population (jumlah_pen)
* family number (jumlah_kk)
* area (luas_wilay) in Km squared
* Population Density (kepadatan_)

Please use 7-zip Zstandard to un-compressed the file. This is the best compression format, and you all are missing out if not using it: 
https://github.com/mcmilk/7-Zip-zstd/releases

For Linux and OSX users, you could run 7z ZSTD from Wine / Crossover / PlayonLinux

https://www.winehq.org/
