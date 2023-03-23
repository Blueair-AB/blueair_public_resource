# Discovery Sample
Current discovery response detail blow.
``` json
{
    "header": {
        "name": "Discover.Response",
        "payloadVersion": "3",
        "messageId": "45741343-9fa0-4ed9-9765-944ff71e3733",
        "namespace": "Alexa.Discovery"
    },
    "payload": {
        "endpoints": [
            {
                "friendlyName": "C",
                "capabilities": [
                    {
                        "capabilityResources": {
                            "friendlyNames": [
                                {
                                    "value": {
                                        "text": "filter",
                                        "locale": "en-US"
                                    },
                                    "@type": "text"
                                }
                            ]
                        },
                        "version": "3",
                        "interface": "Alexa.InventoryLevelSensor",
                        "properties": {
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "level"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "configuration": {
                            "replenishment": {
                                "value": "Default",
                                "@type": "DashReplenishmentId"
                            },
                            "measurement": {
                                "@type": "Percentage"
                            }
                        },
                        "type": "AlexaInterface",
                        "instance": "filter"
                    },
                    {
                        "properties": {
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "connectivity"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "type": "AlexaInterface",
                        "version": "3.2",
                        "interface": "Alexa.EndpointHealth"
                    },
                    {
                        "properties": {
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "powerState"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "type": "AlexaInterface",
                        "version": "3",
                        "interface": "Alexa.PowerController"
                    },
                    {
                        "properties": {
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "brightness"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "type": "AlexaInterface",
                        "version": "3",
                        "interface": "Alexa.BrightnessController"
                    },
                    {
                        "capabilityResources": {
                            "friendlyNames": [
                                {
                                    "value": {
                                        "assetId": "Alexa.Setting.FanSpeed"
                                    },
                                    "@type": "asset"
                                }
                            ]
                        },
                        "version": "3",
                        "interface": "Alexa.RangeController",
                        "properties": {
                            "nonControllable": false,
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "rangeValue"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "configuration": {
                            "supportedRange": {
                                "maximumValue": 3,
                                "precision": 1,
                                "minimumValue": 0
                            }
                        },
                        "type": "AlexaInterface",
                        "instance": "Fan.Speed"
                    },
                    {
                        "capabilityResources": {
                            "friendlyNames": [
                                {
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-US"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-GB"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-CA"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-AU"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-IN"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Nacht-Modus",
                                        "locale": "de-DE"
                                    },
                                    "@type": "text"
                                }
                            ]
                        },
                        "version": "3",
                        "interface": "Alexa.ToggleController",
                        "properties": {
                            "nonControllable": false,
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "toggleState"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "instance": "Night Mode",
                        "type": "AlexaInterface"
                    },
                    {
                        "capabilityResources": {
                            "friendlyNames": [
                                {
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-US"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-GB"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-CA"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-AU"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-IN"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Automatikmodus",
                                        "locale": "de-DE"
                                    },
                                    "@type": "text"
                                }
                            ]
                        },
                        "version": "3",
                        "interface": "Alexa.ToggleController",
                        "properties": {
                            "nonControllable": false,
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "toggleState"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "instance": "Auto Mode",
                        "type": "AlexaInterface"
                    },
                    {
                        "type": "AlexaInterface",
                        "version": "3",
                        "interface": "Alexa"
                    }
                ],
                "endpointId": "1e697f0c-4cc1-4dbd-8ead-181401535378",
                "description": "Air Purifier by Blueair",
                "displayCategories": [
                    "AIR_PURIFIER"
                ],
                "cookie": {},
                "manufacturerName": "Blueair"
            },
            {
                "friendlyName": "b4",
                "capabilities": [
                    {
                        "capabilityResources": {
                            "friendlyNames": [
                                {
                                    "value": {
                                        "text": "filter",
                                        "locale": "en-US"
                                    },
                                    "@type": "text"
                                }
                            ]
                        },
                        "version": "3",
                        "interface": "Alexa.InventoryLevelSensor",
                        "properties": {
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "level"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "configuration": {
                            "replenishment": {
                                "value": "Default",
                                "@type": "DashReplenishmentId"
                            },
                            "measurement": {
                                "@type": "Percentage"
                            }
                        },
                        "type": "AlexaInterface",
                        "instance": "filter"
                    },
                    {
                        "properties": {
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "connectivity"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "type": "AlexaInterface",
                        "version": "3.2",
                        "interface": "Alexa.EndpointHealth"
                    },
                    {
                        "properties": {
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "powerState"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "type": "AlexaInterface",
                        "version": "3",
                        "interface": "Alexa.PowerController"
                    },
                    {
                        "properties": {
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "brightness"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "type": "AlexaInterface",
                        "version": "3",
                        "interface": "Alexa.BrightnessController"
                    },
                    {
                        "capabilityResources": {
                            "friendlyNames": [
                                {
                                    "value": {
                                        "assetId": "Alexa.Setting.FanSpeed"
                                    },
                                    "@type": "asset"
                                }
                            ]
                        },
                        "version": "3",
                        "interface": "Alexa.RangeController",
                        "properties": {
                            "nonControllable": false,
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "rangeValue"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "configuration": {
                            "supportedRange": {
                                "maximumValue": 3,
                                "precision": 1,
                                "minimumValue": 0
                            }
                        },
                        "type": "AlexaInterface",
                        "instance": "Fan.Speed"
                    },
                    {
                        "capabilityResources": {
                            "friendlyNames": [
                                {
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-US"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-GB"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-CA"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-AU"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-IN"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Nacht-Modus",
                                        "locale": "de-DE"
                                    },
                                    "@type": "text"
                                }
                            ]
                        },
                        "version": "3",
                        "interface": "Alexa.ToggleController",
                        "properties": {
                            "nonControllable": false,
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "toggleState"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "instance": "Night Mode",
                        "type": "AlexaInterface"
                    },
                    {
                        "capabilityResources": {
                            "friendlyNames": [
                                {
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-US"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-GB"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-CA"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-AU"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-IN"
                                    },
                                    "@type": "text"
                                },
                                {
                                    "value": {
                                        "text": "Automatikmodus",
                                        "locale": "de-DE"
                                    },
                                    "@type": "text"
                                }
                            ]
                        },
                        "version": "3",
                        "interface": "Alexa.ToggleController",
                        "properties": {
                            "nonControllable": false,
                            "retrievable": true,
                            "supported": [
                                {
                                    "name": "toggleState"
                                }
                            ],
                            "proactivelyReported": true
                        },
                        "instance": "Auto Mode",
                        "type": "AlexaInterface"
                    },
                    {
                        "type": "AlexaInterface",
                        "version": "3",
                        "interface": "Alexa"
                    }
                ],
                "endpointId": "1dec2068-4382-45f6-8bc3-b19058dd1c3f",
                "description": "Air Purifier by Blueair",
                "displayCategories": [
                    "AIR_PURIFIER"
                ],
                "cookie": {},
                "manufacturerName": "Blueair"
            }
        ]
    }
}

```
