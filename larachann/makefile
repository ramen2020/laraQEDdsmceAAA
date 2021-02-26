larack_dir = ../laradock
class=

up:
	cd $(larack_dir) && docker-compose up -d nginx mysql workspace
work:
	cd $(larack_dir) && docker-compose exec workspace bash
db:
	cd $(larack_dir) && docker-compose exec mysql bash
down:
	cd $(larack_dir) && docker-compose down
ps:
	cd $(larack_dir) && docker-compose ps
stop:
	cd $(larack_dir) && docker-compose stop
test:
	cd $(larack_dir) && docker-compose exec workspace php artisan test
unit_test:
	cd $(larack_dir) && docker-compose exec workspace php artisan test --filter=${class}
open:
	open http://localhost