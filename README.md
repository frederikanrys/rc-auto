# rc-auto
This is a project to build a 3D printed remote controlled car. The car body is based on the [Cybertruck](https://www.tesla.com/cybertruck) from Tesla. The car is designed to be 3D printed and to be controlled by a remote control.

![Cybertruck](images/Cybertruck-back.jpeg)


# Bill of Material
There is a combination of printed parts and off the shelf parts. The off the shelf parts are listed in the table below. The printed parts are listed in the table below that.

## Off the shalf parts
| Check                                        | Description                          | # | Geert | Fre | Comment                        | Link                                                                                                                            |
|----------------------------------------------|--------------------------------------|---|-------|-----|--------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
|                                              | Motor + ESC                          | 1 | 1 + 3 |     | Test Pulsar B-20, B-40         | [aliexpress.com](https://nl.aliexpress.com/item/1005006742987156.html)                                                          |
| <span style="color: green;">&#10004;</span>  | Motor Mount                          | 1 |       | 6   |                                | [conrad.be](https://www.conrad.be/nl/p/reely-536014c-reserveonderdeel-motorhouder-1418556.html)                                 |
| <span style="color: green;">&#10004;</span>  | Pinion                               | 1 | 5+5+7 |     | 12T, 15T, 20T                  | [absima.be](https://www.absima.shop/pp/alu-pinion-32dp/module0-8-20T.html)                                                      |
| <span style="color: green;">&#10004;</span>  | Battery                              | 1 | 4     | 6   | 5200mAh, 2S, 80C               | [amazon.de](https://www.amazon.de/-/en/dp/B08X4GF9DK?psc=1&ref=ppx_yo2ov_dt_b_product_details)                                  |
|                                              | Servo                                | 1 | 3     |     |                                | [aliexpress.com](https://nl.aliexpress.com/item/1005007301836255.html)                                                          |
|                                              | Receiver + Transmitter               | 1 | 3     |     |                                | [conrad.be](https://www.conrad.be/nl/p/reely-gen4-rc-pistoolzender-2-4-ghz-aantal-kanalen-4-incl-ontvanger-2267650.html)        |
| <span style="color: green;">&#10004;</span>  | Differential                         | 2 |       | 12  |                                | [conrad.be](https://www.conrad.be/nl/p/reely-10003-reserveonderdeel-differentieel-712524.html)                                  |
| <span style="color: green;">&#10004;</span>  | Differential - Drive shaft Connector | 2 |       | 12  |                                | [conrad.be](https://www.conrad.be/nl/p/reely-536026-reserveonderdeel-conische-tandwielen-met-differentieeluitgang-1301672.html) |
| <span style="color: green;">&#10004;</span>  | Dog bone                             | 4 | 8     | 12  | needs thread lock!             | [amazon.de](https://www.amazon.de/-/en/dp/B08FMJXFCH?psc=1&ref=ppx_yo2ov_dt_b_product_details)                                  |
| <span style="color: green;">&#10004;</span>  | Bearing - 10X15X4                    | 8 |       | 40  |                                | [aliexpress.com](https://nl.aliexpress.com/item/32904604356.html)                                                               |
| <span style="color: green;">&#10004;</span>  | Bearing - 5X10X4                     | 8 |       | 40  |                                | [aliexpress.com](https://nl.aliexpress.com/item/32905646461.html)                                                               |
| <span style="color: green;">&#10004;</span>  | Hot glue                             |   | Y     | Y   |                                |                                                                                                                                 |
| <span style="color: green;">&#10004;</span>  | CA glue                              |   | Y     | Y   |                                |                                                                                                                                 |
| <span style="color: green;">&#10004;</span>  | Duct tape                            |   | Y     | Y   |                                |                                                                                                                                 |
| <span style="color: green;">&#10004;</span>  | Screws M3                            | 1 | 3     | 3   | 440 pieces                     | [Amazon.de](https://www.amazon.de/-/nl/dp/B0B3MGZ7T2/ref=pd_day0fbt_thbs_d_sccl_2/257-0877788-9470555)                          |
| <span style="color: green;">&#10004;</span>  | Screws M4 (100mm or 70mm)            | 4 |       | 20  | Bottom wing - plate connection |                                                                                                                                 |
|                                              | Wheel Fastener                       | 4 |       | 16  |                                | [aliexpress.nl](https://nl.aliexpress.com/item/32947782005.html)                                                                |
| <span style="color: green;">&#10004;</span>  | Threaded inserts                     | 8 | Y     | Y   | Diff cover                     | [ruthex.de](https://www.ruthex.de/en/collections/gewindeeinsatze/m3)                                                            |
| <span style="color: green;">&#10004;</span>  | Rubber band                          | 4 | Y     | Y   | Shock                          |                                                                                                                                 |


## printed parts
| Check                                         | Description                                                    | Material       | # | Geert   | Fre | Comment                                                       |
|-----------------------------------------------|----------------------------------------------------------------|----------------|---|---------|-----|---------------------------------------------------------------|
| <span style="color: green;">&#10004;</span>   | Receiver box                                                   | PLA            | 1 |         | 5   | will use OOTB                                                 |
|                                               | Battery box - top                                              | PLA            | 1 |         |     | Lenne will make this one.                                     |
| <span style="color: green;">&#10004;</span>   | Servo - steering rod                                           | PLA            | 1 |         | 5   | will use OOTB                                                 |
|                                               |                                                                |                |   |         |     |                                                               |
| <span style="color: green;">&#10004;</span>   | [Wheel - tire](stl/wheel-tire.stl)                             | TPU-A95        | 4 | 12+4    | 8   | Last set of 4 are from test vehicle                           |
| <span style="color: green;">&#10004;</span>   | [Wheel - rim](stl/wheel-rim.stl)                               | PLA            | 4 | 12+4    | 8   | Last set of 4 are from test vehicle                           |
|                                               | [Wheel - hex](stl/wheel-hex.stl)                               | PLA            | 4 |         | 30  | Still need to make 2mmx1cm hex pins                           |
| <span style="color: green;">&#10004;</span>   | [Plate - center](stl/plate-center.stl)                         | PLA            | 1 | 2+3     | 1   | 3 cannot handle long M4 x 100mm, 2 have a minor defect on top |
| <span style="color: green;">&#10004;</span>   | [Plate - front](stl/plate-bottom-front.stl)                    | PLA            | 1 | 6       | 1   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Plate - rear](stl/plate-bottom-rear.stl)                      | PLA            | 1 | 6       | 1   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Plate - Diff - top](stl/plate-diff-top.stl)                   | PLA            | 2 | 12      | 2   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Wing - bottom](stl/wing-bottom.stl)                           | PLA or TPU-A98 | 4 | 24      | 8   | use TPU to absorb impact                                      |
| <span style="color: green;">&#10004;</span>   | [Wing - top](stl/wing-top.stl)                                 | PLA or TPU-A98 | 4 | 24      | 8   | use TPU to absorb impact                                      |
|                                               | [Caster - claw](stl/turn-caster)                               | TPU-A98        | 4 | 24+20   | 4   | use TPU to absorb impact                                      |
|                                               | [Caster - turning](stl/turn-front)                             | PLA            | 2 | 12      | 2   |                                                               |
|                                               | [Caster - fixed](stl/turn-rear)                                | PLA            | 2 | 15      | 2   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Shock - slider](stl/Shock.stl)                                | PLA            | 8 | 56      | 8   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Shock - cap](stl/Shock.stl)                                   | PLA            | 8 | 56      | 8   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Steer - turn-left](stl/steering-left.stl)                     | PLA            | 1 | 6       | 6   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Steer - turn-right](stl/steering-right.stl)                   | PLA            | 1 | 6       | 6   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Steer - connector](stl/steering-connect.stl)                  | PLA or TPU-A95 | 1 | 6       | 6   | TPU acts as servo saver                                       |
| <span style="color: green;">&#10004;</span>   | [Steer - rings](stl/steering-rings.stl)                        | PLA            | 2 |         | 12  |                                                               |
| <span style="color: green;">&#10004;</span>   | [Steer - top](stl/steering-top.stl)                            | PLA            | 1 | 6       | 6   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Steer - rod - 67mm](stl/steering-arm-67mm.stl)                | PLA or TPU-A95 | 2 | 10      | 12  | TPU acts as servo saver                                       |
| <span style="color: green;">&#10004;</span>   | [Driveshaft - bearing](stl/driveshaft-bearing-28x12.5x8.stl)   | PLA            | 1 |         | 6   |                                                               |
|                                               | [Driveshaft - gear 48T](stl/driveshaft-gear-48T.stl)           | PLA            | 1 |         |     | Will use 60T                                                  |
| <span style="color: green;">&#10004;</span>   | [Driveshaft - gear 60T](stl/driveshaft-gear-60T.stl)           | PLA            | 1 |         | 6   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Driveshaft - axle](stl/driveshaft.stl)                        | PLA or ABS     | 1 |         | 6   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Bumper](stl/bumper.stl)                                       | TPU-A95        | 1 |         | 6   | use TPU to absorb impact                                      |
| <span style="color: green;">&#10004;</span>   | [Cybertruck - front](stl/Cybertruck-front.stl)                 | PLA            | 1 |         | 5   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Cybertruck - front - holder](stl/Cybertruck-front-holder.stl) | PLA            | 1 |         | 5   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Cybertruck - rear](stl/Cybertruck-rear.stl)                   | PLA            | 1 |         | 5   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Cybertruck - rear - holder](stl/Cybertruck-rear-holder.stl)   | PLA            | 1 |         | 5   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Cybertruck - decal](stl/Cybertruck-decal.stl)                 | PLA            | 1 |         | 5   |                                                               |
| <span style="color: green;">&#10004;</span>   | [Cybertruck - decal](stl/Cybertruck-logo.stl)                  | PLA            | 1 |         | 5   |                                                               |

