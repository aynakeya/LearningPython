Bilibili Favourite DownLoader<br>
b站收藏夹下载器<br>
<br>
Make sure you have both python and lulu(or you-get if it works XD)<br>
请确保安装了python3 和 lulu(或you-get 如果能用的话)<br>
<br>
Make sure you Favourite list is public<br>
请确保你的收藏夹是公开的<br>
~~It is -old.py<br>~~
~~删掉的是-old版本的<br>~~
~~<br>~~
~~enter the url with '/' in the end (e.g enter your fav: https://space.bilibili.com/10003632/#!/favlist?fid=20677228/)~~<br>
~~请在地址的最后面加上'/'( 例子：enter your fav: https://space.bilibili.com/10003632/#!/favlist?fid=20677228/)~~<br>
~~<br>~~
~~enter the number of video you want download(from newest)(e.g enter your number: 503 ==> stand for download newest 503 videos)<br>~~
~~输入想要下载的视频数量(从最新的一个开始计算)(例子：enter your number: 503 ==> 下载前503个视频)<br>~~
~~<br>~~
~~enter the path you want to save the videos:<br>~~
~~输入视频保存位置<br>~~
~~<br>~~
~~enter the path you want to save the data(full path with document name):<br>~~
~~输入保存的文件名字<br>~~
<br>
python BiliFavDownLD.py [-h] [-s] [-n] [-d] [-c] [-v] [-m] [--method] favlink<br>
Options:<br>
-h/--help: help<br>
-s/--saveroute: saveroute(default: current dir)<br>
-n/--number: number u want to download(default: 1)<br>
-d: export data<br>
-c: download cover<br>
-v: download video<br>
-m: use muliprocessing<br>
--method: use which to download(default:you-get)<br>
enjoy :)<br>
<br>
Dec.4.2017 : Fisrt Upload.<br>
Dec.5.2017 : Add Pictures DownLoad<br>
Mar.28.2018 : Rewrite getdata() by using json<br>
Apr.3.2018 : Use lulu instead of you-get<br>
May.20.2018 : Rewrite<br>
May.22.2018 : Add multiprocess download.<br>
May.22.2018 : Fix Bugs, support on windows now.<br>
July.9.2018 : Rewrite.<br>
July.28.2018 : Fix api. /video --> /arc.<br>
Nov.29.2018 : Fix bug: parse link error fixed.<br>