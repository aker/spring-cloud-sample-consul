# spring-cloud-sample-consul

Demo application to run spring cloud on consul

## Running the sample

 1. Install Consul, Please see the [installation documentation](https://www.consul.io/intro/getting-started/install.html) for instructions on how to install Consul. 
 1. In the first window, run: `./src/main/bash/local_run_consul.sh` and wait for it to start up
 1. In the second window, build the application using `mvn clean package spring-boot:run`

You should see two servers being registered on web-application ([http://localhost:8500](http://localhost:8500/))

