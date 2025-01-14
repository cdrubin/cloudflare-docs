---
# Code generated by logshare-api. DO NOT EDIT.

title: Device posture results
pcx_content_type: configuration
weight: 21
---

# Device posture results

The descriptions below detail the fields available for `device_posture_results`.

{{<table-wrap>}}

| Field | Value | Type |
| -- | -- | -- |
| ClientVersion | The Zero Trust client version at the time of upload. | string |
| DeviceID | The device ID that performed the posture upload. | string |
| DeviceManufacturer | The manufacturer of the device that the Zero Trust client is running on. | string |
| DeviceModel | The model of the device that the Zero Trust client is running on. | string |
| DeviceName | The name of the device that the Zero Trust client is running on. | string |
| DeviceSerialNumber | The serial number of the device that the Zero Trust client is running on. | string |
| DeviceType | The Zero Trust client operating system type. | string |
| Email | The email used to register the device with the Zero Trust client. | string |
| OSVersion | The operating system version at the time of upload. | string |
| PolicyID | The posture check ID associated with this device posture result. | string |
| PostureCheckName | The name of the posture check associated with this device posture result. | string |
| PostureCheckType | The type of the Zero Trust client check or service provider check. | string |
| PostureEvaluatedResult | Whether this posture upload passes the associated posture check, given the requirements posture check at the time of the timestamp. | bool |
| PostureExpectedJSON | JSON object of what the posture check expects from the Zero Trust client. | object |
| PostureReceivedJSON | JSON object of what the Zero Trust client actually uploads. | object |
| Timestamp | The date and time the corresponding device posture upload was performed (for example, '2021-07-27T00:01:07Z'). | int or string |
| UserUID | The uid of the user who registered the device. | string |

{{</table-wrap>}}
