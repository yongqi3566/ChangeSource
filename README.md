# ChangeSource
为LInux系统一键更换软件源的一键脚本和其他替换源/备用镜像的常用脚本


使用方法
下载脚本
Github官方
wget https://raw.githubusercontent.com/BlueSkyXN/ChangeSource/master/changesource.sh
或者

curl https://raw.githubusercontent.com/BlueSkyXN/ChangeSource/master/changesource.sh
本站CDN加速
wget https://cdn.000714.xyz/BlueSkyXN/ChangeSource/master/changesource.sh
或者

curl https://cdn.000714.xyz/BlueSkyXN/ChangeSource/master/changesource.sh
使用脚本
bash changesource.sh
对于Debian默认换源为Fastly CDN的mirror这个源有Fastly的加持对境外主机都有不错的速度。

对于Ubuntu和 CentOS系统都默认换为阿里云的mirror，这个源有阿里云全球CDN的加持，全球都有不错的速度。

对于Debian系统还设置了四套其他的源，阿里云，CloudFront CDN，网易163，中科大的源

请根据需要使用参数一键设置如：

bash changesource.sh cn
bash changesource.sh 163
bash changesource.sh aliyun
bash changesource.sh aws
还原
bash changesource.sh restore
