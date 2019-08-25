build:
	GOOS=linux GOARCH=amd64 go build
	docker build -t billpayment-frame .
	rm billpayment-frame
run:
	docker run billpayment-frame
clean:
	rm consignment-cli