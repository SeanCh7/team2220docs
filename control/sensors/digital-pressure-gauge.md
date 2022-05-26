# Digital Pressure Gauge

## Pinout

| Color  | Function            |
| ------ | ------------------- |
| Brown  | DC+ (500mA)         |
| Black  | Output 1 (Not Used) |
| White  | Output 2 (Not Used) |
| Orange | Analog Output       |
| Blue   | DC- (500mA)         |

## Test Measurements

The table below shows sample voltage readings across a 403Ω load at various pressures. Based on the readings and the fact that the output is linear, the voltage can be approximated using the following formula:&#x20;

$$
psi*0.0395+2.18
$$

| Measured PSI | Actual Voltage |
| ------------ | -------------- |
| 0            | 2.18           |
| 70           | 4.94           |
| 75           | 5.14           |
| 108          | 6.42           |
| 109          | 6.46           |
| 109.8        | 6.52           |

​
