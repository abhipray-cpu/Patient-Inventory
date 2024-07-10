SHELL=/bin/bash

up:
	@echo "Starting up services..."
	docker-compose -f docker-compose.yml up -d
	@echo "Services started successfully."

down:
	@echo "Shutting down services..."
	docker-compose -f docker-compose.yml down
	@echo "Services shut down successfully."