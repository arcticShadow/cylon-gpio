# Commands

## analogRead(pin_number)

Public: Returns an integer value that represents the analog read from the sensor.

- **pin_number** -  The pin number for which to return data

Returns ´integer´ Current analog sensor value.

## upperLimit(limit)

Public: Sets an upper limit for the sensor, that when exceeded, triggers a notification event of the same name.

- **limit** -  The upper limit that triggers notification event

Returns null.

## lowerLimit(limit)

Public: Sets an lower limit for the sensor, that when exceeded, triggers a notification event of the same name.

- **limit** -  The lower limit that triggers notification event

Returns null.