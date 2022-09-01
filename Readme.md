1. pwd (make sure you are under directory "project/" )
2. npm install
3. node app.js
4. open your browser http://localhost
open 80 port on linux
> sudo apt-get install libcap2-bin 
> sudo setcap cap_net_bind_service=+ep `readlink -f \`which node\`` 