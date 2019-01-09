## Introduction

This is the Ubisoft [Zabbix](https://www.zabbix.com) instance deployment


## Configuration

The following table lists the configurable parameters of the Zabbix chart and their default values.

Parameter | Description | Default
--------- | ----------- | -------
`zbx-srv.enabled` | Create L7 Ingress | `true`
`db.persistence.enabled` | Create DB persistence volume | `true`