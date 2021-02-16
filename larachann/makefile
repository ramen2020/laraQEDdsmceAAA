larack_dir = ../laradock

up:
	cd $(larack_dir) && docker-compose up -d nginx mysql workspace
work:
	cd $(larack_dir) && docker-compose exec workspace bash
down:
	cd $(larack_dir) && docker-compose down
ps:
	cd $(larack_dir) && docker-compose ps
stop:
	cd $(larack_dir) && docker-compose stop
open:
	open http://localhost