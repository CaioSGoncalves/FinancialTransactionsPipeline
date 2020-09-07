all: test build

test:
	pytest tests

build:
	rm -f ./dist/*
	cp ./main.py ./dist
	zip -r dist/jobs.zip jobs
