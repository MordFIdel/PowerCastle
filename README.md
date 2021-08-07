# PowerCastle
An all-purpose Power manager and UPS for IoT projects<br/><br/>A smart power manager and UPS board for IoT project developers with bunch of smart features.<br/>There are many power converter boards in the market but it was hard to find one with all the needed<br/> power management functions in one place. <br/> Some 18650 converters features one or two voltage outputs, little or no user controls, or just converter<br/> without UPS fucntion. Some other high-end ones are just tailored for Raspberry Pi.<br/><br/>After years of having to buy/make different power supplies for our boards, sensors, peripherals, MCUs<br/> and other non-standard<br/>requirements, each one tailored to a specific need, we decided to finally end this struggle<br/>by providing a one-stop solution. PowerCastle features converters, UPS and smart controls for any<br/> power supply need.<br/>One of its distinct feature is  "power in the loop" used for firmware update without power interuption.<br/><br/>You can now concentrate on the rest of your awesome projects wthout having to worry about power.
# Features and Specifications<br/>
* **Power supply**
<br/>18650 rechargeable battery
<br/>USB C
<br/>Power terminal for alternate power supply
* **Outputs**
<br/>3v3 1A
<br/>5v 1A
<br/>3v-30v (8W)
* **Smart Charge Controller**
<br/>OverCharge protection
<br/>Auto-adjust charge parameters
* **Power Manager**
<br/>Zero delay between switching (battery/external power)
<br/>Independent outputs control
<br/>Charger control
<br/>USB input detect (3v3 and 5v mcu)
<br/>Battery voltage sense (3v3 and 5v mcu)
* **Compact Physical Dimension**
<br/>53 mm X 95 mm <br/>
<br/>To ensure full flexibility and versatility, PowerCastle does not feature its own controller. All controls are application dependent and fully customizable by the user.
<br/>![PowwerCastle_pic](https://user-images.githubusercontent.com/88499684/128438393-10a2e281-13a6-441c-a555-328e18007e9e.png)
<br/><br/>
* **Use Cases**
<br/>PowerCastle is all-purpose, therefore it can be used with virtually all hardware within it power capacity <br/> such as mobile and remote systems, autonomous robot, breakout boards, sensors etc. Below, firmware update is done seemlessly without having to first switch/power down the Arduino Uno board. This is applicable to Raspberry Pi or to perform safe bootloader upload for custom boards.
<br/><br/> The controls, accessible via the standard 8-pin, 2.54mm female header makes the PowerCastle application flexible. Each individual outputs can be switched independently via attached host MCU, USB input power is detectable, battery voltage level is measured via ADC, charging unit is controllable via host MCU.
<br/><br/>
![Power_in_the_loop](https://user-images.githubusercontent.com/88499684/128581765-8858691c-b717-4b83-b27b-a0ea01307167.jpg)
<br/><br/>
![20210807_135252](https://user-images.githubusercontent.com/88499684/128600963-79a5fda9-9ac6-4260-85a1-8ba452b591c7.jpg)


