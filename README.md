李沐 动手学深度学习 tut

本地映射：
jupyter notebook
本地ssh -L 8888:Localhost:8888 liuqingyun@124.16.151.179 -p 22203


git config --global -l

Git报错：fatal: unable to access OpenSSL SSL_read: Connection was reset, errno 10054
git config --global http.sslVerify false

fatal: unable to access ‘https://XXX: Failed onnect to github. com port 443: Timed out
git config --global --unset http.proxy
git config --global --unset https.proxy

git config --global http.proxy http://127.0.0.1:10809
git config --global https.proxy http://127.0.0.1:10809