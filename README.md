# ugc-cos-auth
cos-auth server for UGC upload

# 使用步骤
1. 填写config文件，设置签名所需参数
2. 将server.js, config.js 上传至你的服务器
3. node server.js, 建议配合pm2, forever, supervisor等使用
4. 访问服务器ip:端口号，即可获取签名，建议配置域名解析和nginx反向代理后使用
