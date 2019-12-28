# org.gnome.NautilusDevel.flatpak
org.gnome.NautilusDevel.flatpak linux flatpak

Собрал уже очень давно

sudo apt install flatpak

sudo add-apt-repository ppa:alexlarsson/flatpak

sudo apt update

sudo apt install gnome-software-plugin-flatpak

apt purge flatpak

apt install flatpak

flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo

flatpak remote-delete --force flathub

flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo

flatpak install flathub org.gnome.Platform//3.28

теперь при выборе user заработает открываем директорию с org.gnome.NautilusDevel.flatpak и из терминала выполняем ниже

flatpak install --bundle org.gnome.NautilusDevel.flatpak

Открываем любой другой проводник в нем ПКМ выбираем открыть с помощью nemo 

Как все это работает https://radikal.ru/video/hY1k48ta5VH так же gnome-control-center-3.32.1 который я использовал даже в 19.04 взять можно тут https://github.com/Griggorii/gnome-control-center-3.32.1
