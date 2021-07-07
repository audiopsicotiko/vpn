#como instalar vpn
primero agregar el comando

wget https://raw.githubusercontent.com/audiopsicotiko/vpn/master/vpn.sh

wget https://git.io/vpn -O openvpn-ubuntu-install.sh                  para 20.04

chmod +x vpn.sh

./vpn.sh

reiniciar con sudo shutdown -r now     o service start openvpn y esperar un rato a que se despliegue en la red
