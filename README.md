# Test BirdNET Pi und GitHub

Data should be stored and analyzed within GitHUb
# File conversion
[] done with new version

# Sync into GitHub
* [Quelle](https://stackoverflow.com/questions/11111562/rsync-copy-over-only-certain-types-of-files-using-include-option) 
> rsync -zarv --prune-empty-dirs --include "\*/" --include="\*.mp3" --exclude="*" /home/pi/BirdSongs/Extracted/By_Common_Name/ /home/pi/BirdNET-GitHub/
* [QUelle](https://stackoverflow.com/questions/38593855/replacing-commas-in-a-csv-file-with-sed-for-mongoimport) 
 > sed -i 's/\;/\,/g' /home/pi/BirdNET-GitHub/BirdDB.txt 

# Git Command
* git add --all
* git push -u origin master
* git commit -am KOMENTAR
* git config --global credential.helper cache
