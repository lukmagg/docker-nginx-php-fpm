To create the image go inside the folder and write the following:

	docker build -t nginx-php-fpm .


To create a container with this image:

	docker run -d --name nginx-php-fpm -p 80:80 nginx-php-fpm
