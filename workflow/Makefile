.PHONY: apt images

update packages:
	sudo apt update
	sudo apt upgrade -y
images:
	docker images
ps:
	docker ps
	docker ps -a
logs-back:
	docker logs workflow-backend
up-back:
	docker start workflow-backend
down-back:
	docker stop workflow-backend