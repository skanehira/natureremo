# Nature Remo API Client for Go

## Install

```
$ go get -u github.com/tenntenn/natureremo
```

## Supported API

### Global API

http://swagger.nature.global

|                 Endpoint                | Method |     Status       |
|-----------------------------------------|:------:|:----------------:|
|/1/users/me                              | GET    |:heavy_check_mark:|
|/1/users/me                              | POST   |:heavy_check_mark:|
|/1/detectappliance                       | POST   |                  |
|/1/appliances                            | GET    |                  |
|/1/appliances                            | POST   |                  |
|/1/appliance_orders                      | POST   |                  |
|/1/appliances/{appliance}/delete         | POST   |                  |
|/1/appliances/{appliance}                | POST   |                  |
|/1/appliances/{appliance}/aircon_settings| POST   |                  |
|/1/appliances/{appliance}/signals        | GET    |                  |
|/1/appliances/{appliance}/signals        | POST   |                  |
|/1/appliances/{appliance}/signal_orders  | POST   |                  |
|/1/signals/{signal}                      | POST   |                  |
|/1/signals/{signal}/delete               | POST   |                  |
|/1/signals/{signal}/send                 | POST   |                  |
|/1/devices/{device}                      | POST   |                  |
|/1/devices/{device}/delete               | POST   |                  |
|/1/devices/{device}/temperature_offset   | POST   |                  |
|/1/devices/{device}/humidity_offset      | POST   |                  |