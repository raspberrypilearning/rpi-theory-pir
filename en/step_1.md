### About PIR motion sensors

In this project, we are going to be using a **p**assive **i**nfra**r**ed (PIR) motion sensor. You have probably seen these before, as they are often used in burglar alarm systems.

If the temperature of an object or organism is above absolute zero (that's −273.15°C!), it emits infrared radiation. Infrared wavelengths are not visible to the human eye, but they can be detected by the electronics inside a PIR sensor.

The sensor is regarded as passive because it doesn't send out any signal in order to detect movement. It works by adjusting itself to the infrared signature of the room it's in and then watching for changes. Any object moving through the room will disturb the infrared signature, and the PIR module detects this disturbance.

![PIR sensor](images/pir_module.png)

We don't need to worry about the inner workings of the motion sensor. What we're interested in are its three pins, which can be used to connect it to the Raspberry Pi.
