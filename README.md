#/bin/bash

echo -e "\033[1;32mC R I E   U M   U S U A R I O"
echo -e "\033[1;31mD I G I T E  O  N O M E  D O  U S U A R I O  Q U E  D E S E J A"
read -p " " user
useradd -M -s /bin/false $user
sleep 2
clear
echo -e "\033[1;31mS E N H A  P A R A  O  U S U A R I O :\033[0m $user "
read -p " " pass
( echo "$pass";echo "$pass" ) | passwd $user 2> /dev/null
sleep 1
echo -e "\033[1;32m#########################"
echo -e "\033[1;31mCONTA CRIADA COM SECESSO"
echo -e "\033[1;32m#####"
echo -e "\033[1;31mU S E R\033[0m $user "
echo -e "\033[1;32m#####"
echo -e "\033[1;31mP A S S W O R D\033[0m $pass "
echo -e "\033[1;32m#########P R O N T O###########"# 
Test2
