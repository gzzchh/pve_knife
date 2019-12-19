# pve_knife
一 Quelques livres jio qui facilitent l'utilisation de Proxmox / 些让操作Proxmox更简单的jio本
# Cet élément est temporairement modifié. / 本项目暂时缓更.

# Caractéristiques / 功能
* Remplacer Enterprise Edition Source par Community Source / 替换企业版源为社区源  
* Remplacer la source de mise à jour Debian par une image domestique (Alibaba Cloud) / 替换Debian更新源为国内镜像(阿里云)  
* Après le remplacement, mettez à niveau le système (facultatif) / 替换完成,后升级系统(可选)  
* Serveur de mise à niveau rétrograde SNIProxy (facultatif) / SNIProxy反代升级服务器(可选)  
* Installer des commandes communes / 安装常用的命令  
* Ajouter une confirmation à l'exécution de la commande rm cp mv avec un alias dans le fichier de configuration bash / 在bash配置文件里用别名添加对rm cp mv命令执行时的确认  
* Supprimer la fenêtre contextuelle sans abonnement lors de la connexion / 去除登陆的时候那个没有订阅的弹窗  
* Accélérez la connexion SSH (supprimez UseDNS) / 加快SSH登陆(去掉UseDNS)  

# Fonctionnalités écrites mais pas encore ajoutées au menu  /写出来但是还没有加入到菜单的功能 
* Installation rapide de NodeJS (fil supplémentaire en option, commutateur optionnel vers la source Tsinghua) / 快速安装NodeJS(可选附加Yarn,可选切换至清华源) 
* Activer la mise en miroir Taobao pour NodeJS (facultatif) / 为NodeJS启用淘宝镜像(可选)
* Installez rapidement Docker / 快速安装Docker

# Plan suivant (Todo List) / 接下来的计划
* Support pour installer plus de logiciels rapidement (Webmin, Portainer, FRP, Syncthing) / 支持快速安装更多的软件(Webmin,Portainer,FRP,Syncthing)
* Mettez la fonction écrite dans le menu / 将写好的功能摆到菜单里
* Implémentez la détection IP, jugez automatiquement les clients nationaux et étrangers et utilisez les sources correspondantes / 实现IP检测,自动判断国内外并且使用相应的源
* Pour détecter l'existence du fichier de fonction, s'il n'existe pas, téléchargez-le pour simplifier le script (référez-vous à l'idée de LinuxGSM) / 实现检测函数文件是否存在,若不存在则下载,使脚本更加精简(参考LinuxGSM的思想)

# Comment utiliser / 食用方法
Clonez ce projet et exécutez pve_knife.sh. Vous aurez le choix entre un menu / 克隆本项目,执行pve_knife.sh即可.会有菜单让你选择

