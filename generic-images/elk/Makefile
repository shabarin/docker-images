IMAGE_NAME=webreactor/elk
IMAGE_TAG=v0.0.3
IMAGE=$(IMAGE_NAME):$(IMAGE_TAG)

build:
	docker build -t $(IMAGE) .
	docker tag -f $(IMAGE) $(IMAGE_NAME):latest

push:
	docker push $(IMAGE)
	docker push $(IMAGE_NAME):latest

