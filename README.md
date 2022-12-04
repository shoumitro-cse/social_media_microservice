# social_media_microservice
This is a social media micro service app.


## Nginx setup for api getway

```
cd social_media_microservice
sudo cp nginx_server.conf /etc/nginx/sites-available/social_media
sudo ln -s /etc/nginx/sites-available/social_media /etc/nginx/sites-enabled
sudo nginx -t
sudo systemctl restart nginx
````


## API from different microservice

```
http://social-media.com/user-auth/
http://social-media.com/messanger/
http://social-media.com/notification/
````
