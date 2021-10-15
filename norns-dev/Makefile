.PHONY: build run clean

build:
	docker build -t wwinder/norns-dev .

run:
	docker run --rm -it \
		--ulimit rtprio=95 --ulimit memlock=-1 --shm-size=256m \
		wwinder/norns-dev
