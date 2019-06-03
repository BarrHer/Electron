Pré requis :<br>
NodeJS,<br>
sudo apt-get install npm <br>
/ ou <br>
sudo apt-get install python g++ make <br>
wget http://nodejs.org/dist/node-latest.tar.gz <br>
tar xvfvz node-latest.tar.gz <br>
cd node-v0.10.21 (replace a version with your own) <br>
./configure <br>
make <br>
sudo make install <br>
<br><br>
Dépendence electron : <br>
npm install <br>
npm install mysql <br>
npm install electron-packager <br>
 <br><br>
Utilisation : <br>
Direct, <br>
npm start <br>
/ ou <br>
Version executable, <br>
electron-packager . electron-nazza --overwrite --asar --platform=linux --arch=x64 --prune=false --out=executable
Et executer le fichier du nom "electron-nazza1-linux-x64"

