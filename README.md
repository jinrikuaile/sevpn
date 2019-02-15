#sevpn


wget https://raw.githubusercontent.com/jinrikuaile/sevpn/master/sevpn && bash sevpn





在上传sevpn配置文件处，我删除了
rm -f sevpn.ovpn* >/dev/null 2>&1
避免因上传失败而无法获取配置文件（最近transfer那个上传有时候会出问题，显示Could not save metadata），你可以使用ftp连接上服务器，自行从服务器中获取。（文件在vpnserver中）
