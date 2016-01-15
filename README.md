# test files for lisa

Test of LISA:

--------
15/01/2016

tar zvxf molden5.0.tar.gz 

cd molden5.0

make


ls -ltr

the two binary files are: molden and gmolden 

./molden won't work for now.

start your X server

ssh -X ...

ssh -Y ...    if you trust LISA :)


./molden ../molecule.zmat

-------------::::step 2:::::-----------

qsub lisa.job

you will get the two files: lisa.job.numbers





watch -n 3 qstats -u myname

helpdesk@surfsara.nl

ask my questions about packages and modeulles
software: 
https://userinfo.surfsara.nl/systems/lisa/software

