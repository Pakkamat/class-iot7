![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1cdti/hw/get/6310301036/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301036",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "21"
}
```

## Get firmware version
```
Topic: v1cdti/hw/get/6310301036/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301036",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "firmware",
    "value"     : "ver_2"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1cdti/hw/get/6310301036/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301036",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "location",
    "value"     : "Bangkok"
}
```

## Set geo-location or location placement
```
Topic: v1cdti/hw/set/6310301036/model-01/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301036",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "location",
    "value"     : "Bangkok"
}
```

## Monitor machine sensor
```
Topic: v1cdti/hw/Monitor/6310301036/model-01/WSH-SN001
Payload: {
    "action"    : "Monitor",
    "project"   : "6310301036",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "speed_round",
    "value"     : "10"
}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1cdti/hw/set/6310301036/model-01/WSH-SN001
Payload: {
    "action"    : "Monitor",
    "project"   : "6310301036",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "status",
    "value"     : "maint"
}
```