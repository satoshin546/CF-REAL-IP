# CF-REAL-IP

1、 创建sh并运行生成conf

2、 在nginx配置中增加一行：
include /usr/local/nginx/conf/cloudflare_ip.conf;

3、nginx -t 检查并生效

4、chrontab -e 添加定时任务

