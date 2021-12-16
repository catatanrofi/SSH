# SSH
Cara menginstal SSH

<h3>Instalasi</h3>
<p>$ apt-get update -y</p>
<p>$ apt-get upgrade -y</p>
<p>$ apt-get install openssh-server</p>
<h3>Konfigurasi port SSH</h3>
<p>$ nano /etc/ssh/sshd_config</p>
<p>• Hilangkan tanda pagar [#] pada port 22</p>
<p>• Kemudian tekan tombol ctrl+x lalu tekan y lalu Enter</p>
<h3>Restart SSH</h3>
<p>$ systemctl restart ssh</p>
