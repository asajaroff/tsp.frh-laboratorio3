DOCKER_TAG = php-server:v1-template

target: build

build: 
	docker buildx build \
	-t $(DOCKER_TAG) \
	--load \
	.

run:
	docker run $(DOCKER_TAG)