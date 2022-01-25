- 👋 Hi, I’m @THC999999999
- 👀 I’m interested in all informatica sistem
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
THC999999999/THC999999999 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

cd $HOME/ighack/core                                                                                   
update(){                                                                                                             
if wget --spider https://raw.githubusercontent.com/noob-hackers/patchupdateznh/main/ighackpatch.v.1 2>/dev/null; then
cd $HOME/ighack/core
rm *.txt
echo "igg" > patch.txt
else
clear
echo
echo
echo
echo
echo
echo
echo
echo
echo -e "\e[92m             IGHACK LATEST \e[91mNO PATCH AVAILABLE FOR NOW...!\e[92m\e[0m"
echo -e "\e[96m                ╔═══════════════════════════════════╗\e[0m"
echo -e "\e[96m                ║       \e[93mIghack\e[96m Uptodate\e[93m V1.2\e[96m        ║\e[0m"
echo -e "\e[96m                ║        No Patch \e[93mIs Available\e[96m      ║\e[0m"
echo -e "\e[96m                ║                                   ║\e[0m"
echo -e "\e[96m                ╚═══════════════════════════════════╝\e[0m"
echo
echo
echo
echo
echo
sleep 5.0
cd $HOME/ighack
bash ighack.sh
fi
}
update
 
option(){
if [ -f "$HOME/ighack/core/patch.txt" ];then
$dbox
else
echo
fi
}
option
 
dbox(){
clear
echo
echo
echo
echo
echo
echo
echo
echo
echo -e "\e[92m                   IGHACK LATEST PATCH V1 IS AVAILABLE\e[0m"
echo -e "\e[96m                ╔═══════════════════════════════════╗\e[0m"
echo -e "\e[96m                ║  \e[93mIghack\e[96m Patch Is avaialbe\e[93m V1.0\e[96m    ║\e[0m"
echo -e "\e[96m                ║    To PAtch The \e[93mIghack\e[96m Tool       ║\e[0m"
echo -e "\e[96m                ║                                   ║\e[0m"
echo -e "\e[96m                ║         Select \e[92my\e[96m to update\e[96m        ║\e[0m"
echo -e "\e[96m                ║                (\e[93mOR\e[96m)               \e[96m║\e[0m"
echo -e "\e[96m                ║        Select \e[91mt\e[96m to terminate\e[96m      ║\e[0m"
echo -e "\e[96m                ╚═══════════════════════════════════╝\e[0m"
echo
echo
echo
echo
echo
echo -en "\e[32mSELECT OPTION [\e[93my/\e[93mt\e[32m]\e[96m: \e[0m "
read patcher
if [ $updater = y ];then
clear
sleep 0.5
