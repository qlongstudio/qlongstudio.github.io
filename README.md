Failed to connect to github.com port 443:connection timed out
处理方法
git config --global --unset http.proxy
git config --global --unset https.proxy



git config --global http.sslBackend "openssl"