# Monitor Entities for Inactivity Blueprint

This blueprint for Home Assistant allows you to monitor entities for inactivity and receive notifications when they have been inactive for a specified period of time.

## Features

- Monitors multiple entities for inactivity.
- Allows customization of the timeout duration.
- Sends notifications when entities have been inactive for the specified period of time.

## Installation

1. Copy the blueprint YAML code into your Home Assistant instance.
2. Use the blueprint to create automations in your Home Assistant configuration.
3. Customize the blueprint parameters to monitor your desired entities and set the timeout duration.

## Usage
1. Add the blueprint to your Home Assistant configuration.
2. Create automations based on this blueprint in your Home Assistant UI.
3. Configure the monitoring entities and timeout duration according to your needs.
4. Save and activate the automations.

## Parameters

- **Monitoring Entities**: Select the entities to monitor for inactivity.
- **Timeout**: Specify the duration after which entities are considered inactive.
- **Actions**: Specify the actions to be executed when entities are inactive. Use `{{ entity_name }}` and `{{ defined_timeout }}` as variables in your actions.

## Tested with MQTT Sensors

This blueprint has been tested with MQTT sensors, including temperature sensors, motion sensors, and thermostats.
