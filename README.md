# archlinux-kde-xfce--script-install-uefi-nogrub   
РЕЖИМ UEFI и Legacy

Для установки  ArchLinux(KDE vs Xfce) вам необходимо загрузиться с установочного диска ArchLinux и в теринале выполнить   

1 wget https://git.io/arc.sh

2 chmod +x arc.sh

3 ./arc.sh

Данный скрипт позваляет установить ArchLinux(KDE vs Xfce), как рядом с Windows так и произвести чистую установку.
___________________________________________________________________________________________________________
Файловая система для root раздела "ext4"

Файловая система для home раздела "ext4"

Файловая система для boot раздела "FAT32" < так требует стандарт UEFI(загрузчик для ArchLinux systemD)

Файловая система для boot раздела "ext2" < в legacy режиме
__________________________________________________________________________________________________________
Список пакетов установленных по умолчанию

пакеты драйверов xorg-server xorg-drivers (после установки можно будет установить/дополнить )

програмы: pulseaudio-bluetooth ark exfat-utils unrar alsa-utils  unzip ntfs-3g pulseaudio-equalizer-ladspa  

есть возможность выбора  программ для установки

flameshot filezilla
htop gparted
neofetch screenfetch
gwenview
steam steam-native-runtime 
spectacle vlc 
elegram-desktop
gvfs-afc - iphone
gvfs-mtp - android

KDE или Xfce на выбор!!!

предоставлен выбор zsh или bash
zsh(С таким же плагином и подцветкой как в установочном образе archlinux ) 

так же можно установить Mozilla Firefox(russian) или GoogleChrome на выбор!

__________________________________________________________________________________________________________

удален только браузер  браузер konqueror если устанавливаете KDE

__________________________________________________________________________________________________________

По всем вопросам пишите https://vk.com/poruncov или https://t.me/poruncov

Более подробная информация по ArchLinux в группе в ВК https://vk.com/arch4u
__________________________________________________________________________________________________________

Нашли ошибку сообщите!!!!
