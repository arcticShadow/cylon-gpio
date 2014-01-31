# Commands

## turnOn()

Public: Starts the motor.

Returns true | nil.

## turnOff()

Public: Stops the motor.

Returns true | nil.

## toggle()

Public: Sets the state of the motor to the oposite of the current state, if motor is on then sets it to off.

Returns true | nil.

## speed(speed_value)

Public: Sets the speed of the motor to the value provided in the speed param, speed value must be an integer between 0 and 255.

- **speed_value** -  The speed value for which to return data

Returns integer_value.

## currentSpeed()

Public: Returns the current speed of the motor as an integer between 0 and 255.

Returns integer_value.
