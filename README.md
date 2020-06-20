# Control servos and a camera on a Rasbery PI in GO

## Right now with is just a hello world to get cross paltform builds running

## Build
The aim is to build an artifact that will run on a rasbery PI, to build the artifact, trageting as Rasbery PI 3
run `GOARM=7 GOARCH=arm GOOS=linux go build hello-control.go` 