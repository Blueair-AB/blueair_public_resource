# Discovery Sample
Current discovery response detail blow.
``` json
{
    "header": {
        "namespace": "Alexa.Discovery",
        "name": "Discover.Response",
        "payloadVersion": "3",
        "messageId": "4dd18cf2-d0a7-4005-a708-e34b32ccef8e"
    },
    "payload": {
        "endpoints": [
            {
                "endpointId": "169c1fd6-c4e4-4793-9d93-5e9d1f943917",
                "friendlyName": "jack",
                "description": "Air Purifier by Blueair",
                "manufacturerName": "Blueair",
                "displayCategories": [
                    "AIR_PURIFIER"
                ],
                "cookie": {},
                "capabilities": [
                    {
                        "type": "AlexaInterface",
                        "interface": "Alexa.InventoryLevelSensor",
                        "instance": "filter",
                        "version": "3",
                        "properties": {
                            "supported": [
                                {
                                    "name": "level"
                                }
                            ],
                            "retrievable": true,
                            "proactivelyReported": true
                        },
                        "configuration": {
                            "measurement": {
                                "@type": "Percentage"
                            },
                            "replenishment": {
                                "@type": "DashReplenishmentId",
                                "value": "Default"
                            }
                        },
                        "capabilityResources": {
                            "friendlyNames": [
                                {
                                    "@type": "text",
                                    "value": {
                                        "text": "filter",
                                        "locale": "en-US"
                                    }
                                }
                            ]
                        }
                    },
                    {
                        "type": "AlexaInterface",
                        "interface": "Alexa.EndpointHealth",
                        "version": "3.2",
                        "properties": {
                            "supported": [
                                {
                                    "name": "connectivity"
                                }
                            ],
                            "proactivelyReported": true,
                            "retrievable": true
                        }
                    },
                    {
                        "interface": "Alexa.PowerController",
                        "version": "3",
                        "type": "AlexaInterface",
                        "properties": {
                            "supported": [
                                {
                                    "name": "powerState"
                                }
                            ],
                            "proactivelyReported": true,
                            "retrievable": true
                        }
                    },
                    {
                        "type": "AlexaInterface",
                        "interface": "Alexa.BrightnessController",
                        "version": "3",
                        "properties": {
                            "supported": [
                                {
                                    "name": "brightness"
                                }
                            ],
                            "proactivelyReported": true,
                            "retrievable": true
                        }
                    },
                    {
                        "type": "AlexaInterface",
                        "interface": "Alexa.RangeController",
                        "instance": "Fan.Speed",
                        "version": "3",
                        "properties": {
                            "supported": [
                                {
                                    "name": "rangeValue"
                                }
                            ],
                            "proactivelyReported": true,
                            "retrievable": true,
                            "nonControllable": false
                        },
                        "capabilityResources": {
                            "friendlyNames": [
                                {
                                    "@type": "asset",
                                    "value": {
                                        "assetId": "Alexa.Setting.FanSpeed"
                                    }
                                }
                            ]
                        },
                        "configuration": {
                            "supportedRange": {
                                "minimumValue": 0,
                                "maximumValue": 3,
                                "precision": 1
                            }
                        }
                    },
                    {
                        "type": "AlexaInterface",
                        "interface": "Alexa.ToggleController",
                        "instance": "Night Mode",
                        "version": "3",
                        "properties": {
                            "supported": [
                                {
                                    "name": "toggleState"
                                }
                            ],
                            "proactivelyReported": true,
                            "retrievable": true,
                            "nonControllable": false
                        },
                        "capabilityResources": {
                            "friendlyNames": [
                                {
                                    "@type": "text",
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-US"
                                    }
                                },
                                {
                                    "@type": "text",
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-GB"
                                    }
                                },
                                {
                                    "@type": "text",
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-CA"
                                    }
                                },
                                {
                                    "@type": "text",
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-AU"
                                    }
                                },
                                {
                                    "@type": "text",
                                    "value": {
                                        "text": "Night Mode",
                                        "locale": "en-IN"
                                    }
                                },
                                {
                                    "@type": "text",
                                    "value": {
                                        "text": "Nacht-Modus",
                                        "locale": "de-DE"
                                    }
                                }
                            ]
                        }
                    },
                    {
                        "type": "AlexaInterface",
                        "interface": "Alexa.ToggleController",
                        "instance": "Auto Mode",
                        "version": "3",
                        "properties": {
                            "supported": [
                                {
                                    "name": "toggleState"
                                }
                            ],
                            "proactivelyReported": true,
                            "retrievable": true,
                            "nonControllable": false
                        },
                        "capabilityResources": {
                            "friendlyNames": [
                                {
                                    "@type": "text",
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-US"
                                    }
                                },
                                {
                                    "@type": "text",
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-GB"
                                    }
                                },
                                {
                                    "@type": "text",
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-CA"
                                    }
                                },
                                {
                                    "@type": "text",
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-AU"
                                    }
                                },
                                {
                                    "@type": "text",
                                    "value": {
                                        "text": "Auto Mode",
                                        "locale": "en-IN"
                                    }
                                },
                                {
                                    "@type": "text",
                                    "value": {
                                        "text": "Automatikmodus",
                                        "locale": "de-DE"
                                    }
                                }
                            ]
                        }
                    },
                    {
                        "type": "AlexaInterface",
                        "interface": "Alexa",
                        "version": "3"
                    }
                ]
            }
        ]
    }
}

```
