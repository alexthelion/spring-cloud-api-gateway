# Spring Cloud Api Gateway
This project contains a demo of Api Gateway using:
* Spring Cloud 
* Hystrix
* Actuator

Metrics scraped by: Prometheus

## Example of gateway metrics
> gateway_requests_seconds_count{httpMethod="GET",httpStatusCode="200",outcome="SUCCESSFUL",routeId="Test-F",routeUri="http://localhost:8081",status="OK",} 1.0
> gateway_requests_seconds_sum{httpMethod="GET",httpStatusCode="200",outcome="SUCCESSFUL",routeId="Test-F",routeUri="http://localhost:8081",status="OK",} 0.1838946
> HELP gateway_requests_seconds_max  
> TYPE gateway_requests_seconds_max gauge
> gateway_requests_seconds_max{httpMethod="GET",httpStatusCode="200",outcome="SUCCESSFUL",routeId="Test-F",routeUri="http://localhost:8081",status="OK",} 0.1838946
