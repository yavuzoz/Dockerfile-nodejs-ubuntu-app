apt-get update
apt-get install curl -y
curl -sL https://deb.nodesource.com/setup_14.x | bash
apt-get install nodejs -y
mkdir node-app
cd node-app/
echo 'console.log("nodejsapp from ubuntu..");' > index.js
node index.js
