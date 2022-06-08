 1  apt-get update
    2  apt-get install curl -y
    4  curl -sL https://deb.nodesource.com/setup_10.x |bash
    7  apt-get install nodejs -y
   10  cd opt
   11  mkdir node-app
   13  cd node-app
   15  echo 'console.log("nodejsapp from ubuntu...");'>index.js
   18  node index.js