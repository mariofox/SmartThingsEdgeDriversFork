To install a custom driver, these 3 guides were useful:

https://github.com/SmartThingsCommunity/smartthings-cli

https://community.smartthings.com/t/st-edge-add-fingerprints-to-released-edge-drivers/238197/8

https://community.smartthings.com/t/tutorial-creating-drivers-for-zigbee-devices-with-smartthings-edge/229502

The command used for installing was:

smartthings edge:drivers:package -I --token=TOKEN
(run from path: C:\Users\USER\PycharmProjects\SmartThingsEdgeDriversCustom\drivers\SmartThings\zwave-lock)

This command asks for the channel and the hub, but figure how to install it in several hubs.