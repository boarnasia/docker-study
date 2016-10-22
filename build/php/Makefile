IMAGE_NAME := my-php:fpm

build: distclean
	docker build -t $(IMAGE_NAME) ./

rebuild: distclean build

distclean:
	docker rmi $(IMAGE_NAME)

