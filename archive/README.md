# Fri3d RC Car (Archive)

> **Note:** This is the archived version of the original Fri3d RC Car design. For the latest version with Traxxas Slash 4x4 compatible drivetrain components, see the [main project](../README.md).

This is a project to build a 3D printed remote controlled car. The car body is based on the [Cybertruck](https://www.tesla.com/cybertruck) from Tesla. The car is designed to be 3D printed and to be controlled by a remote control.

As this is not a beginner project, it is recommended to have some experience with 3D printing and remote controlled cars.
The project is an open-source project and can be used by anyone. We originally designed this project for [Fri3d Camp](https://fri3d.be/) to build 5 cars with children and play with them during the camp.

![Cybertruck](../images/Cybertruck-back.jpeg)


# How to start?
There is a combination of printed parts and off the shelf parts. Both off the shelf parts and printed parts are listed in the [Bill of Material](#Bill-of-Material). Off the shelf parts can be bought from various online stores such as the one proposed in the Link column.
The printed parts are available in the [stl](stl) directory. The original design files are available in the [shapr](shapr) directory.
The printed parts can be printed on a printer with a maximum size of 25cm x 25cm x 25cm. Most parts can be printed with PLA, but some parts are to be printed with TPU (to absorb impact).

The car is designed with durability in mind. You will notice we do not print the parts that need to be very strong such as the differentials and dog bones. You should buy them online. It makes the car a bit more expensive to build, but it will last much longer. 
For more durability, some parts are to be printed in TPU (flexible filament). i.e.: the bumper, the caster claws, and the top and bottom of the wings,... 
That way, they can absorb the impact of a crash without breaking.

# Assembly
Once you have the printed the parts on your printer and bought some of the parts online, you can start to assemble the car as described in the following documents:
1. [Part 1 - Body](manual/part1-body.pdf) 
2. [Part 2 - Front & Back](manual/part2-front-back.pdf)
3. [Part 3 - Final](manual/part3-final.pdf)

Happy assembling and Good Luck!


# Bill of Material
## Off the shelf parts
| Description               | #   | Comment                        | Link                                                                                                                                                 |
| ------------------------- | --- | ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Motor + ESC               | 1   | Test Pulsar B-20, B-40         | [aliexpress.com](https://nl.aliexpress.com/item/1005006742987156.html)                                                                               |
| Motor Mount               | 1   |                                |                                                                                                                                                      |
| Pinion                    | 1   | 12T, 15T, 20T                  | [absima.be](https://www.absima.shop/pp/alu-pinion-32dp/module0-8-20T.htm?shop=absima_en&SessionId=&a=article&ProdNr=2310348&t=19114&c=19132&p=19132) |
| Battery                   | 1   | 5200mAh, 2S, 80C               | [amazon.de](https://www.amazon.de/-/en/dp/B08X4GF9DK?psc=1&ref=ppx_yo2ov_dt_b_product_details)                                                       |
| Servo                     | 1   |                                | [aliexpress.com](https://nl.aliexpress.com/item/1005007301836255.html)                                                                               |
| Receiver + Transmitter    | 1   |                                |                                                                                                                                                      |
| Bearing - 10X15X4         | 8   |                                |                                                                                                                                                      |
| Bearing - 5X10X4          | 8   |                                |                                                                                                                                                      |
| Screws M3                 | 1   | 440 pieces                     | [Amazon.de](https://www.amazon.de/-/nl/dp/B0B3MGZ7T2/ref=pd_day0fbt_thbs_d_sccl_2/257-0877788-9470555)                                               |
| Screws M4 (100mm or 70mm) | 4   | Bottom wing - plate connection |                                                                                                                                                      |
| Wheel Fastener            | 4   |                                |                                                                                                                                                      |
| Threaded inserts          | 8   | Diff cover                     |                                                                                                                                                      |
| Rubber band               | 4   | Shock                          |                                                                                                                                                      |


## Printed parts
Depending on the print settings, you will need around 2KG of Filament to print all the parts. Instead of PLA, you can also use PETG or ABS.


| Check                                       | Description                                                    | Material       | #   | Comment                                                       |
| ------------------------------------------- | -------------------------------------------------------------- | -------------- | --- | ------------------------------------------------------------- |
| <span style="color: green;">&#10004;</span> | Receiver box                                                   | PLA            | 1   | Will use OOTB                                                 |
|                                             | Servo - steering rod                                           |                | 1   |                                                               |
|                                             |                                                                |                |     |                                                               |
| <span style="color: green;">&#10004;</span> | [Wheel - tire](stl/wheel-tire.stl)                             | TPU-A95        | 4   | Last set of 4 are from test vehicle                           |
| <span style="color: green;">&#10004;</span> | [Wheel - rim](stl/wheel-rim.stl)                               | PLA            | 4   | Last set of 4 are from test vehicle                           |
|                                             | [Wheel - hex](stl/wheel-hex.stl)                               | PLA            | 4   | Still need to make 2mmx1cm hex pins                           |
| <span style="color: green;">&#10004;</span> | [Plate - center](stl/plate-center.stl)                         | PLA            | 1   | 3 cannot handle long M4 x 100mm, 2 have a minor defect on top |
| <span style="color: green;">&#10004;</span> | [Plate - front](stl/plate-bottom-front.stl)                    | PLA            | 1   |                                                               |
| <span style="color: green;">&#10004;</span> | [Plate - rear](stl/plate-bottom-rear.stl)                      | PLA            | 1   |                                                               |
| <span style="color: green;">&#10004;</span> | [Plate - Diff - top](stl/plate-diff-top.stl)                   | PLA            | 2   | Print with 100% fill rate                                     |
| <span style="color: green;">&#10004;</span> | [Plate - battery - holder](stl/plate-battery-holder.stl)       | PLA            | 1   |                                                               |
| <span style="color: green;">&#10004;</span> | [Wing - bottom](stl/wing-bottom.stl)                           | PLA or TPU-A98 | 4   | Use TPU to absorb impact                                      |
| <span style="color: green;">&#10004;</span> | [Wing - top](stl/wing-top.stl)                                 | PLA or TPU-A98 | 4   | Use TPU to absorb impact                                      |
|                                             | [Caster - claw](stl/turn-caster)                               | TPU-A98        | 4   | Use TPU to absorb impact                                      |
|                                             | [Caster - turning](stl/turn-front)                             | PLA            | 2   |                                                               |
|                                             | [Caster - fixed](stl/turn-rear)                                | PLA            | 2   |                                                               |
| <span style="color: green;">&#10004;</span> | [Shock - slider](stl/Shock.stl)                                | PLA            | 8   |                                                               |
| <span style="color: green;">&#10004;</span> | [Shock - cap](stl/Shock.stl)                                   | PLA            | 8   |                                                               |
| <span style="color: green;">&#10004;</span> | [Steer - turn-left](stl/steering-left.stl)                     | PLA            | 1   |                                                               |
| <span style="color: green;">&#10004;</span> | [Steer - turn-right](stl/steering-right.stl)                   | PLA            | 1   |                                                               |
| <span style="color: green;">&#10004;</span> | [Steer - connector](stl/steering-connect.stl)                  | PLA or TPU-A95 | 1   | TPU acts as servo saver                                       |
| <span style="color: green;">&#10004;</span> | [Steer - rings](stl/steering-rings.stl)                        | PLA            | 2   |                                                               |
| <span style="color: green;">&#10004;</span> | [Steer - top](stl/steering-top.stl)                            | PLA            | 1   |                                                               |
| <span style="color: green;">&#10004;</span> | [Steer - rod - 67mm](stl/steering-arm-67mm.stl)                | PLA or TPU-A95 | 2   | TPU acts as servo saver                                       |
| <span style="color: green;">&#10004;</span> | [Driveshaft - bearing](stl/driveshaft-bearing-28x12.5x8.stl)   | PLA            | 1   |                                                               |
|                                             | [Driveshaft - gear 48T](stl/driveshaft-gear-48T.stl)           | PLA            | 1   | Print with 100% fill rate                                     |
| <span style="color: green;">&#10004;</span> | [Driveshaft - gear 60T](stl/driveshaft-gear-60T.stl)           | PLA            | 1   | Print with 100% fill rate                                     |
| <span style="color: green;">&#10004;</span> | [Driveshaft - axle](stl/driveshaft.stl)                        | PLA or ABS     | 1   | Print with 100% fill rate                                     |
| <span style="color: green;">&#10004;</span> | [Bumper](stl/bumper.stl)                                       | TPU-A95        | 1   | Use TPU to absorb impact                                      |
| <span style="color: green;">&#10004;</span> | [Cybertruck - front](stl/Cybertruck-front.stl)                 | PLA            | 1   |                                                               |
| <span style="color: green;">&#10004;</span> | [Cybertruck - front - holder](stl/Cybertruck-front-holder.stl) | PLA            | 1   |                                                               |
| <span style="color: green;">&#10004;</span> | [Cybertruck - rear](stl/Cybertruck-rear.stl)                   | PLA            | 1   |                                                               |
| <span style="color: green;">&#10004;</span> | [Cybertruck - rear - holder](stl/Cybertruck-rear-holder.stl)   | PLA            | 1   |                                                               |
| <span style="color: green;">&#10004;</span> | [Cybertruck - decal](stl/Cybertruck-decal.stl)                 | PLA            | 1   |                                                               |
| <span style="color: green;">&#10004;</span> | [Cybertruck - logo](stl/Cybertruck-logo.stl)                   | PLA            | 1   |                                                               |

