# social_media_microservice



## Nginx setup for api getway

```
cd social_media_microservice
sudo cp nginx_server.conf /etc/nginx/sites-available/social_media
sudo ln -s /etc/nginx/sites-available/social_media /etc/nginx/sites-enabled
sudo nginx -t
sudo systemctl restart nginx
````

