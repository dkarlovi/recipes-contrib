docker-start:
	docker-compose -f ./docker-compose.yaml -f ./.infra/docker-compose/docker-compose.$(APP_ENV).yaml up -d
.PHONY: docker-up

docker-stop:
	docker-compose down
.PHONY: docker-down

docker-start-dev:
	docker-compose -f ./docker-compose.yaml -f ./.infra/docker-compose/docker-compose.dev.yaml up -d
.PHONY: docker-start-dev

docker-start-prod:
	docker-compose -f ./docker-compose.yaml -f ./.infra/docker-compose/docker-compose.prod.yaml up -d
.PHONY: docker-start-prod

docker-start-test:
	docker-compose -f ./docker-compose.yaml -f ./.infra/docker-compose/docker-compose.test.yaml up -d
.PHONY: docker-start-test

docker-build:
	docker-compose build
.PHONY: docker-build

docker-pull:
	docker-compose pull
.PHONY: docker-pull

docker-push:
	docker-compose push
.PHONY: docker-push

docker-logs:
	docker-compose logs -f
.PHONY: docker-logs
