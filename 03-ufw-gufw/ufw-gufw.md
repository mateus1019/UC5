#03 - UFW / GUFW no Linux Mint
Comandos
sudo ufw status
sudo ufw enable
sudo ufw allow 22/tcp
sudo ufw allow 80/tcp
sudo ufw deny 23/tcp
sudo ufw status verbose
O que foi feito
Ativei o firewall UFW no Linux Mint, liberei as portas 22 e 80,
bloqueei a porta 23 (Telnet) e confirmei o status.
Testei também a interface gráfica GUFW para ligar/desligar e criar regras.
Observação
Firewall ativado para proteger a máquina contra acessos indevidos.
