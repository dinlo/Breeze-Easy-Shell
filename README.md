# Breeze-Easy-Shell

cd /root/
wget https://raw.githubusercontent.com/Brizovsky/Breeze-Easy-Shell/master/breeze.sh -r -N -nd
cat >> /root/.bashrc <<END
alias breeze='cd /root/
sh breeze.sh'
END
exit
