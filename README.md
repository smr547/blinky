# blinky
A two led blinky using state-machine.com architecture running on [Arduino DUE hardware](https://store.arduino.cc/products/arduino-due)

## Build

* This project uses the [Quantum Leaps Real Time Embedded Framework (RTEF)](https://www.state-machine.com/products/qp)
* All code for the project is store in the [model file](./blinky.qm)
* This project utilises the [QP/C++ Framework](https://www.state-machine.com/qpcpp/) and all code is written to the [QP/C++ API](https://www.state-machine.com/qpcpp/api.html)
* C/C++ application code (the ``blinky.ino`` file) is generated using the [qm modelling tool](https://www.state-machine.com/products/qm/)
* Generated code is compiled and uploaded using the [Arduino IDE](https://www.arduino.cc/en/software)
