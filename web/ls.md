# ls

## ls -l
```
total 12
-rw-rw-r-- 1 root root 46 Nov 20  2017 base64.txt
-rw-rw-r-- 1 root root 35 Nov 15  2017 flag
-rw-rw-r-- 1 root root 68 Nov 20  2017 hex.txt
```
## ls -Al
```
total 28
-rw-r--r-- 1 lab  lab   220 Apr 26 14:48 .bash_logout
-rw-r--r-- 1 root root 3771 Apr 26 14:48 .bashrc
-rw-rw-r-- 1 root root   34 Nov 19  2017 .hidden
-rw-r--r-- 1 lab  lab   655 Apr 26 14:48 .profile
-rw-rw-r-- 1 root root   46 Nov 20  2017 base64.txt
-rw-rw-r-- 1 root root   35 Nov 15  2017 flag
-rw-rw-r-- 1 root root   68 Nov 20  2017 hex.txt
```
## ls -al
```
total 36
drwxr-xr-x 1 root root 4096 Apr 26 14:48 .
drwxr-xr-x 1 root root 4096 Apr 26 14:48 ..
-rw-r--r-- 1 lab  lab   220 Apr 26 14:48 .bash_logout
-rw-r--r-- 1 root root 3771 Apr 26 14:48 .bashrc
-rw-rw-r-- 1 root root   34 Nov 19  2017 .hidden
-rw-r--r-- 1 lab  lab   655 Apr 26 14:48 .profile
-rw-rw-r-- 1 root root   46 Nov 20  2017 base64.txt
-rw-rw-r-- 1 root root   35 Nov 15  2017 flag
-rw-rw-r-- 1 root root   68 Nov 20  2017 hex.txt
```
# 參數差異
## -a, --all
```
 do not ignore entries starting with .
 可以顯示隱藏的檔案與目錄。
```
## -A, --almost-all
```
do not list implied . and ..
不輸出.和..
```
## -l
```
 use a long listing format
 顯示完整資訊
```
