# Test BirdNET Pi und GitHub

#Preapre BirdnetPI
* install wiringpi 
> wget https://github.com/TheNextLVL/wiringPi/releases/download/2.46/wiringpi-2.46.deb
> 
> sudo apt install ./wiringpi-2.46.deb
* install witty pi 
* 
> wget http://www.uugear.com/repo/WittyPi2/installWittyPi.sh
> 
> cd wittyPi/
> 
> sudo ./wittyPi.sh 

>sudo crontab -e

> 1 30 6-10 * * * sh /home/pi/birdnetpi_github/birdnetpi_github.sh

Data should be stored and analyzed within GitHUb
# File conversion
* done with new version

# D3.js
* https://observablehq.com/@floatingpurr/observable-twitter-2021

# Sync into GitHub
* [Quelle](https://stackoverflow.com/questions/11111562/rsync-copy-over-only-certain-types-of-files-using-include-option) 
> rsync -zarv --prune-empty-dirs --include "\*/" --include="\*.mp3" --exclude="*" /home/pi/BirdSongs/Extracted/By_Common_Name/ /home/pi/BirdNET-GitHub/
* [QUelle](https://stackoverflow.com/questions/38593855/replacing-commas-in-a-csv-file-with-sed-for-mongoimport) 
 > sed -i 's/\\;/\\,/g' /home/pi/BirdNET-GitHub/BirdDB.txt 

# Git Command
* git add --all
* git push -u origin master
* git commit -am KOMENTAR
* git config --global credential.helper cache
