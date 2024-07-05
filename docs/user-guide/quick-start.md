# Quick start

If you just got the sensor set from the SmartWater team, and want to quickly deploy it without getting into the technical nuance of how everything works, this section is for you. Let's look at the elements you should have:

1. Sentrius LoRa gateway
2. Mobile internet modem with data on it
3. SmartWater sensor

## 1. The gateway & wifi connection

If the gateway comes with a 4G modem, it will be pre-configured for you. Neverthelsee, it is important to know the stepts in case you need to do it your self. There are two important things to be done regarding gateway configuration before sensor deployment: setting up the internet connection; and configuring the server address to which the gateway is supposed to forward the data. Follow the steps below to set up the gateway with the modem (or a wifi connection point):

First thing would be to press the user button (see the sentrius manual for details) for about 5 senconds and then release. The wifi diod will start to blink which means that the gateway created its own wifi network. Connect your computer to that network, just like to any other network. Then go to the local address of the gateway (see the sentrius manual for details).

(image 1 Click on the WiFi tab)
(image 2 Add new WiFi profile)
(image 3 Make sure the wifi profile is activated)
(image 4 Go to LoRa settings tab)
(image 5 Make sure the UDP forwarder is selected)
(image 5 Insert the server address and the port. Ask the administrators for this information)

!!! note

    after you connect the gateway with the modem and your computer is on the same network, you can access the gateway settings on the following address: https://rg1xx29ee63.local/

!!! note

    Steps to factory reset the Sentrius gateway:

    Remove power
    Press and hold the User button
    Restore power while still holding down the User button
    Keep holding down the User button until all LEDs begin to flash
    Release the User button
