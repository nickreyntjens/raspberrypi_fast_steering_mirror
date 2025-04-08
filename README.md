# raspberrypi_fast_steering_mirror

While commercial fast beam steering solutions exist, there is not a simple cheap solution available to the open source community. The project is part of the photonic insecticides movement (https://photonicinsecticides.com) which aims to prevent the extinction of insects.

## Very cheap version with toy servos (cost = 5 euro)

![pic1](pic1.jpeg)
![pic2](pic2.jpeg)
![pic3](pic3.png)

[video 1](https://www.youtube.com/shorts/W5gDEPCPxdw)
[video 2](https://www.youtube.com/shorts/TYv_WdsBpbU)


The 3D printable step files are available in this repo.
This mirror has an expected latency of 20ms (50 hertz pwm delay) + 1 ms (physical movement delay).

A faster version, with more expensive servos like these: 
[kstservo](https://www.kiwi-electronics.com/en/raspberry-pi-global-shutter-camera-c-mount-11346?srsltid=AfmBOorjyt3xhTllkbBb9jNMj-0uA5owiSabHFzQiQZfjXykuc6Kj5gH](https://kstservos.com/collections/helicopter-servos/products/ds215mg-v3-0-digital-metal-gear-micro-servo-3-70kg-cm-0-05sec-for-rc-glider-helicopters)
can hopefully be built in the near future, these would have a latency of 3 ms + 0.5 ms.
When modifying the servo´s by removng the potentiometer and driving the motor directly, a latency of 0.5 ms may be possible.

First surface mirrors are recomended for good optical performence:
[first surface](https://www.edmundoptics.eu/f/first-surface-mirrors/12017/?gad_source=1&gbraid=0AAAAAC6ham1_zjsctIsKr9nlJhu_DgT8E&gclid=CjwKCAjwktO_BhBrEiwAV70jXqvnrjsGfTxdORm-gM6R0VfZ8uMo2aSqY1ZaixHEq3UESwjONfnWnRoC2igQAvD_BwE)


More advanced users may use ultra thin mirrors, making the inirtia small and leading to faster mirror movements.
[ultra thin first surface](https://www.edmundoptics.eu/f/ultra-thin-first-surface-mirrors/40105/)

## Related projects

Fast framerates an tracking on raspberry pi: https://github.com/nickreyntjens/500_fps_raspberry_pi_global_shutter_cam

Laser safety calculator: https://github.com/nickreyntjens/laser_safety_calculator.py
(shows that with correct focal lenght, 1550 nm is safe for eyes at small nominal safety zones)



