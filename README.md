# uptime-kuma

Uptime Kuma — прос­той self-hosted-инс­тру­мент для соз­дания стра­ниц, поз­воля­ющих отсле­живать работос­пособ­ность сер­висов и монито­рин­га, ког­да не нуж­но деталь­но ана­лизи­ровать сис­темные парамет­ры на наб­люда­емых машинах.

docker run -d --restart=always -p 3001:3001 -v uptime-kuma:/app/data --name uptime-kuma louislam/uptime-kuma:1

Более подробную инфу можно найти тут https://uptime.kuma.pet/ 
