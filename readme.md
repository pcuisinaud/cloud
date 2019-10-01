# Cloud 🌥 [![Build Status](https://travis-ci.org/pcuisinaud/cloud.svg?branch=master)](https://travis-ci.org/pcuisinaud/cloud)

## Boot order

1. registry
2. configserver
3. gateway
4. admin

## Config refresh
```
curl -siX POST localhost:8080/actuator/refresh
```
