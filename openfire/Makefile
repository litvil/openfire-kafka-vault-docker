all: build

build:
	@docker build --tag=ruby/openfire:4.2.3 .

release: build
	@docker build --tag=ruby/openfire:$(shell cat VERSION) .
