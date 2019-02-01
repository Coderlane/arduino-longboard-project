# Arduino Longboard

I built this longboard, with the help of some friends, to traverse the hills in my college town.


## Components

The code is split into a few components. The main library is [arduino-longboard](https://github.com/Coderlane/arduino-longboard), the code that ties everything together. That utilizes [arduino-bluetooth](https://github.com/Coderlane/arduino-bluetooth) which works with a [RN42](https://www.microchip.com/wwwproducts/en/RN42) bluetooth module. Then there is the [host](https://github.com/Coderlane/arduino-bluetooth-longboard-host) which runs on the longboard and the [controller](https://github.com/Coderlane/arduino-bluetooth-longboard-controller) which is held in your hand.

* [arduino-longboard](https://github.com/Coderlane/arduino-longboard)
* [arduino-bluetooth](https://github.com/Coderlane/arduino-bluetooth)
* [host](https://github.com/Coderlane/arduino-bluetooth-longboard-host)
* [controller](https://github.com/Coderlane/arduino-bluetooth-longboard-controller)

### Longboard

The mounting of the electronics could use some improvement. V1 included the use of zip ties and tape. V2 used plastic drawer organizers. Here is a video of the V1 mounting.

[![V1 Longboard](https://media.giphy.com/media/1ziCoJi18Odo75gbno/giphy.gif)](https://photos.app.goo.gl/a7vDzqVmQ5DmZSaQA)

### Controller

The controller was 3D printed based on the model of a pistol grip. The inside provided plenty of space for the electronics and it was quite comfortable to grip.

[![Controller](https://i.imgur.com/as3DUbp.jpg)](https://imgur.com/as3DUbp)



### Parts

Here is a basic list of the parts. The deck of the longboard didn't matter as much. However, the trucks were convinently rectangular. The motor and ESC may be overkill, but they certainly helped with power up hill.

|                   Part                   | Quantity | Unit Cost |
|:----------------------------------------:|:--------:|:---------:|
| NTM Prop Drive 50-60 270KV / 2400W MOTOR |     2    |    $45.44 |
| Turnigy Trackstar 150A Gen II ESC        |     2    |    $81.90 |
| Multistar High Capacity 3S 5200mAh Lipo  |     2    |    $29.00 |
| Sparkfun Fio v3                          |     2    |    $34.95 |
| RN42-XV Bluetooth Module                 |     2    |    $24.95 |
| 184mm Caliber BLEMS Downhill Truck       |     2    |    $27.50 |
