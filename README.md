# Watt for Smart Devices
Complementary app to the universe TP-Link Smart home devices of Kasa Smart and Tapo.

<br/><br/>
<p align="center">
<img alt="Screenshot" src="assets/logo.png">
</p>

> :warning: **If you are using mobile browser**: Press the button "View all" to see all the page including the **Roadmap!**
<br/>

Watt is an iOS mobile app developed for the TP-Link's Smart Plugs and Smart Lamps, that allows you to set cost for each kilowatt(kWh) and by doing this you have control of the cost in each device. Also, add support for voice actions using the "Hey Siri".

With this page of GitHub, I hope to develop a small community to report problems with the application and think of solutions.

<br>

Download the Watt app: <br>
[![Apple Store](https://watt-app.com/images/downloads/apple.png)](https://apps.apple.com/us/app/watt-for-smart-devices/id1465004830 "Apple Store link")

<br>

Oficial website:
https://watt-app.com/


# Features

- Daily & monthly energy usage totals and averages and money cost.
- Historical daily and monthly energy usage charts and Runtime (hours that the device was on).
- Turn on/off the device
- Show cumulative energy usage form all devices.
- Support for Siri and the Shortcuts.
- One app supporting the both product lines Kasa and Tapo.

<br/><br/>

|          | Kasa Smart | Tapo | Watt for Smart Devices |
| --- | :---: | :---: | :---: |
| Control Kasa Devices | :heavy_check_mark: | :heavy_multiplication_x: | :heavy_check_mark: |
| Control Tapo Devices | :heavy_multiplication_x: | :heavy_check_mark: | :heavy_check_mark: |
| Apple Shortcuts      | :heavy_check_mark: | :heavy_multiplication_x: | :heavy_check_mark: |
| Siri support from the app | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_check_mark: |
| Night mode (Turn off led) | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_check_mark: |
| Charts (Runtime and energy usage)   | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_check_mark: |
| Live consumption (from all devices) | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_check_mark: |
| Erase Statistics  | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_check_mark: |
| Set price for kWh | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_check_mark: |
| See voltage and Current | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_check_mark: |
| Price | Free | Free | Free |



<br/><br/>

|           <td colspan=3> Kasa Smart  <td colspan=2> Tapo
| Featured | Kasa <br/>HS100, HS103, HS105, HS107, HS200, HS210, HS220, KP105, KP200, KP303, KP400 | Kasa <br/>HS110, HS300 | Kasa <br/>KL50, KL60, KL110, KL120, KL130, LB100, LB110, LB120, LB130, LB200, LB230 | Tapo <br/>P100, P105 | Tapo <br/>L510, L530 |
| --- | :---: | :---: | :---: | :---: | :---: |
| Device Type | Smart Plug and Switch | Smart Plug with Energy Monitoring | Smart Bulb | Smart Plug | Smart Bulb | 
| Turn On/Off | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Get overview each device that are active<br/> in the home screen | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Energy consumption Chart <br/> Daily & monthly |  | :heavy_check_mark: | :heavy_check_mark: | :heavy_multiplication_x: | :heavy_multiplication_x: |
| Daily and monthly cost of the device |   | :heavy_check_mark: | :heavy_check_mark: | | :heavy_check_mark: |
| Runtime Chart <br/> Daily & monthly | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_multiplication_x: | :heavy_multiplication_x: |
| Cumulative energy usage <br/>form all devices |   | :heavy_check_mark: | :heavy_check_mark: |      | :heavy_check_mark: |
| Night Mode (turn off the LEDs)| :heavy_check_mark: *1 | :heavy_check_mark: |      | :heavy_check_mark: |       |
| Erase Runtime statistics | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_multiplication_x: | :heavy_multiplication_x: |
| Erase Consumption statistics |   | :heavy_check_mark: | :heavy_check_mark: | :heavy_multiplication_x: | :heavy_multiplication_x: |
| Siri and Apple Shortcuts | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Set Brightness | Just HS220	 |  | :heavy_check_mark: |  | :heavy_check_mark: |
| Set Color Temperature	 |  |  | Just KL120, KL130, LB120, LB130, LB200, LB230 |    | Just L530 |
| Set Light Color	 |  |  | Just KL130, LB130 and LB230 |    | Just L530  |
	
*1 Due to hardware limitations HS200 v1 and HS220 v2 the night mode does not work. It's working well for HS200 v2 and v3 and HS220 v1 and v3.


<br/><br/>
<p align="center">
<img alt="Screenshot" src="assets/home.png">
</p>
<br/><br/><br/>
<p align="center">
<img alt="Screenshot" src="assets/chart.png">
</p>
<br/><br/>

# Issues

If you have any issue or suggestion, open a new ticket by pressing on the top of this page "issues" then "New issue".


# Others

Link to the App:

[https://apps.apple.com/us/app/watt-for-smart-devices/id1465004830](https://apps.apple.com/us/app/watt-for-smart-devices/id1465004830)

Here you can find the video (old):

[https://youtu.be/zFgz4oVbX0c](https://youtu.be/zFgz4oVbX0c)


# Roadmap

- [x] Show cumulative energy usage form all devices.
- [x] Show energy consumption by last 30 days, month.
- [x] Show daily cost metrics
- [x] Make it work with HS100
- [x] Night Mode (Option to turn off the led light).
- [x] Show more info about each device (Like real-time consumption, Voltage, wireless signal)
- [x] The ability to reset the stats for when a different appliance/device is plugged in and I want to start fresh.
- [x] Create a concept "Room/Spaces" which will aggregate multiple devices.
- [x] Find a way to give commands to Siri to turn on/off device (maybe using Siri shortcut)
- [x] Add support to TP-Link HS300, KP303, KL50, KP200, KP400, HS107, KP100.
- [x] Add support to Smart Bulb KL50, KL50B, KL60, LB200, LB230(E26), LB230.
- [x] Implement Haptic Touch.
- [x] Add support to all Tapo devices.
- [x] Calculate the energy cost for smart switches (HS200, HS210 and HS220) based on Runtime + default/set value consumed energy.
- [ ] Send a weekly email with consumption reports and charts.
- [ ] Export the data to Excel (CSV)
- [ ] Show chart gathering all devices and the total cost.
- [ ] Record the energy consumption hour by hour
- [ ] Show energy consumption by day, bill.
- [ ] The option to define peak and off-peak times and electricity prices.
- [ ] Force reboot, turn Off device then On after 30 seconds turn on again (Helpful for devices like wifi routers connected to the smart plug)
- [ ] Make smart action (like if consumption is lower then specific value turn off(stand-by), or using GPS and when arriving home turn on the light, even use the weather forecast to make action, define amount time before sunset/sunrise action)
- [ ] Make a personalized schedule that  will tell you how much money you will save by turning off your device x hours
- [ ] Set Goals to save energy
- [ ] Add new voice command to change bulb temperature color
- [ ] Add Artificial Intelligence (IA) to detect and send you push notification when some consumption is not right like: leave the refrigerator door open, washer is done.
- [ ] If you have multiple devices connected to single HS110 use artificial intelligence to detect which devices are turned on and off and how much each one of them is spending.
- [ ] Make web version




# FAQ

1 - What is "Night Mode" functionality?
> On all TP-Link plugs and switches there is a light to inform you that the device is active. The problem is that when the device is placed in the room it is annoying to have that LED active. With this feature, you can turn off that LED.

2 - How to activate the "Night Mode"?
> To activate "Night Mode" you will have to follow these steps: Click on the button on the bottom right "▲". Click in one of the circles that will open a screen with information about your device. On that screen, you have a button on the top left for configuration, click on it. Now just go down and you'll find "Night Mode".

3 - Do all devices support "Night Mode"?
> Almost all Kasa Smart devices are supporting, except: "HS200 v1" and "HS220 v2" I believe that is because of hardware limitations.


