阿里云全站加速CDN HTTPS证书自动上传脚本，改自 https://github.com/git9527/aliyun-cdn-https-cert-updater。

使用方法:

1. 确保python已安装Requests(pip install requests)
2. 使用说明
    * 上传新的key文件和cert文件
    
        `python updater.py -i LTAI**** -s aBPGz3**** -d 域名 -p ./certs/*.key -c ./certs/fullchain.cer`

    * 使用已有cert name更新https设置
    
        `python updater.py -i LTAI**** -s aBPGz3**** -d 域名  -n some_name`


阿里云相关接口说明(https://help.aliyun.com/document_detail/89666.html?spm=a2c4g.11186623.6.621.68fb41bfE5XzfB)

